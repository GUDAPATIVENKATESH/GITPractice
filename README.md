VCS (Version Control System)
----------------------------
* This is a software which helps organizations to maintain source code.
* Helps in maintaining history of changes.
* Allows us to maintain track of different releases given to customers.
* It allows parlell development by multiple developers.

### Generations or Types of VCS
#### Local VCS: 
   * simplest form of version control system, and it operates on a single computer without the need for a central server. In an LVCS, changes to files are tracked and managed within the local file system itself, typically through the use of file copies or directories.
   * Scalability is not possible.
#### Centralized VCS:
   * A central server will store the entire history of the project.
   * Developers check out files from this central repository to work on them locally. Once they've made changes, they commit those changes back to the central server.
   * CVCS systems typically have a client-server architecture, where developers interact with the central server over a network connection.
   * Ex: Concurrent Versions System (CVS) and Apache Subversion (SVN).
#### Distributed VCS:
   * In a DVCS, every developer has their own local copy of the entire repository, including its history.
   * Developers can commit changes to their local repository without needing to be connected to a central server. They can also work offline and independently.
   * Changes can be shared between repositories by pushing and pulling changes between them.
   * DVCS systems enable more flexible workflows, branching and merging, and better support for distributed teams.
   * Ex: Git
