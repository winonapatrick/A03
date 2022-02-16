# A03
for IS117

How to use GitHub

The first two things you'll want to do are install git and create a free GitHub account.


How to make a Github Repository:

1) In the upper-right corner of any page, use the  drop-down menu, and select New repository.
Drop-down with option to create a new repository
2) Type a name for your repository.
3) Add a description of your repository.
4) Choose a repository visibility.
5) Click Create repository.

To add a new file to the project, use any text editor you like or run a touch command. To add a file to a commit, you first need to add it to the staging environment. To do this, you can use the git add <filename> command
Run the command git commit -m "Your message about the commit"

Now we'll push the commit in your branch to your new GitHub repo. This allows other people to see the changes you've made. If they're approved by the repository's owner, the changes can then be merged into the primary branch.

To push changes onto a new branch on GitHub, you'll want to run git push origin yourbranchname. GitHub will automatically create the branch for you on the remote repository.

Part 2: Glossary to include these terms in a bulleted list.


Branch: A "branch" is a line of development.
Clone: Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository
Commit: captures a snapshot of the project's currently staged changes
Fetch: a primary command used to download contents from a remote repository
GIT: software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development
Github: provider of Internet hosting for software development and version control using Git
Merge: Git's way of putting a forked history back together again
Merge Conflict: occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file
Push: used to upload local repository content to a remote repository
Pull: let you tell others about changes you've pushed to a branch in a repository on GitHub
Remote: a common repository that all team members use to exchange their changes
Repository: contains all of your project's files and each file's revision history

References:
https://docs.github.com/en/get-started

https://docs.github.com/en/get-started/quickstart/github-glossary

https://www.coredna.com/blogs/what-is-git-and-github-part-two
