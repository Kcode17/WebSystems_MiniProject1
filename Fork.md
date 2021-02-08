## Fork
A GitHub fork is a copy of a repository (repo) that sits in your account rather than the account from which you forked the data from. Once you have forked a repo, you own your forked copy. This means that you can edit the contents of your forked repository without impacting the parent repository.

The Forking Workflow begins with an official public repository stored on a server. But when a new developer wants to start working on the project, they do not directly clone the official repository.
Instead, they fork the official repository to create a copy of it on the server. This new copy serves as their personal public repository—no other developers are allowed to push to it, but they can pull changes from it. 

To integrate the feature into the official codebase, the maintainer pulls the contributor’s changes into their local repository, checks to make sure it doesn’t break the project, merges it into their local master branch, then pushes the master branch to the official repository on the server. The contribution is now part of the project, and other developers should pull from the official repository to synchronize their local repositories.
