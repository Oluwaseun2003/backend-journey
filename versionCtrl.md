# What is version control?

### Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

# What is Git?

### Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel.
### The raw performance characteristics of Git are very strong when compared to many alternatives. Committing new changes, branching, merging and comparing past versions are all optimized for performance. 
### Unlike some version control software, Git is not fooled by the names of the files when determining what the storage and version history of the file tree should be, instead, Git focuses on the file content itself. After all, source code files are frequently renamed, split, and rearranged. The object format of Git's repository files uses a combination of delta encoding (storing content differences), compression and explicitly stores directory contents and version metadata objects.

# Git Commands
- **Git add:** Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.

- **Git branch:** This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.

- **Git checkout:** In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.

- **Git clone:** Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.

- **Git commit:** Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.

- **Git init:** Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.

- **Git merge:** A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.

-  **Git pull:** Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.

- **Git push:** Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset.

###And so on