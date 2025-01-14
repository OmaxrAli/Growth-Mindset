## Git

![Git](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQpVK3RQC6LtSy6ZAV69TsEHZFxKfGSxhfSiMRKCQSVBi76HeALh2H_huzUWy9WgwFGA10&usqp=CAU)

#### What Is Git ?

well **Git** is the most popular **(Version Contro System)** in the world, a version control system records the changes made to our code over time in a special database called repository we can look at our project history and see who has made what changes when and why, and if we screw something up we can easily revert our project back to an earlier state without a version control system we'll have to constantly store copies of the entire project in various folders.

this is very slow and doesn't scale at all especially if multiple people have to work on the same project you would have to constantly toss around the latest code via email or some other mechanisms and then manually merge the changes.

with a version control system we can track our project history and work together
version control systems fall has two categories **centralized** and **distributed** 

### **centralized**
in a centralized system all team members connect to a central server to get the latest copy of the code and to share their changes with others subversion and Microsoft team foundation server are examples of centralized version control systems the problem with the centralized architecture is the single point of failure if the server goes offline we cannot collaborate or save snapshots of our project so we have to wait until the server comes back online.

### **distributed** 
in distributed systems we don't have these problems every team member has a copy of the project with its history on their machine so we can save snapshots of our project locally on our machine if the central server is offline we can synchronize our work directly with others
git and mercurial are examples of distributed version control systems out of all these **git** is the most popular version control system in the world because it's 
1.	free 
2.	open source
3.	fast
4.	scalable

operations like branching and merging are slow and painful in other version control systems like
subversion so git is almost everywhere more than 90% of software projects in the world use git that's why almost every job description for a software developer mentions git
know how it works and how to use it to

### How does it works?

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
![Git Working Flow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

the work flow works through this kind of cycle and by using commands we can atchive this kind of work flow

![Git Cycle Working Flow](https://support.nesi.org.nz/hc/article_attachments/360004194235/Git_Diagram.svg)

### All Git Commands

git-add[1]
Add file contents to the index

git-am[1]
Apply a series of patches from a mailbox

git-archive[1]
Create an archive of files from a named tree

git-bisect[1]
Use binary search to find the commit that introduced a bug

git-branch[1]
List, create, or delete branches

git-bundle[1]
Move objects and refs by archive

git-checkout[1]
Switch branches or restore working tree files

git-cherry-pick[1]
Apply the changes introduced by some existing commits

git-citool[1]
Graphical alternative to git-commit

git-clean[1]
Remove untracked files from the working tree

git-clone[1]
Clone a repository into a new directory

git-commit[1]
Record changes to the repository

git-describe[1]
Give an object a human readable name based on an available ref

git-diff[1]
Show changes between commits, commit and working tree, etc

git-fetch[1]
Download objects and refs from another repository

git-format-patch[1]
Prepare patches for e-mail submission

git-gc[1]
Cleanup unnecessary files and optimize the local repository

git-grep[1]
Print lines matching a pattern

git-gui[1]
A portable graphical interface to Git

git-init[1]
Create an empty Git repository or reinitialize an existing one

gitk[1]
The Git repository browser

git-log[1]
Show commit logs

git-maintenance[1]
Run tasks to optimize Git repository data

git-merge[1]
Join two or more development histories together

git-mv[1]
Move or rename a file, a directory, or a symlink

git-notes[1]
Add or inspect object notes

git-pull[1]
Fetch from and integrate with another repository or a local branch

git-push[1]
Update remote refs along with associated objects

git-range-diff[1]
Compare two commit ranges (e.g. two versions of a branch)

git-rebase[1]
Reapply commits on top of another base tip

git-reset[1]
Reset current HEAD to the specified state

git-restore[1]
Restore working tree files

git-revert[1]
Revert some existing commits

git-rm[1]
Remove files from the working tree and from the index

git-shortlog[1]
Summarize git log output

git-show[1]
Show various types of objects

git-sparse-checkout[1]
Initialize and modify the sparse-checkout

git-stash[1]
Stash the changes in a dirty working directory away

git-status[1]
Show the working tree status

git-submodule[1]
Initialize, update or inspect submodules

git-switch[1]
Switch branches

git-tag[1]
Create, list, delete or verify a tag object signed with GPG

git-worktree[1]
Manage multiple working trees

Ancillary Commands
Manipulators:

git-config[1]
Get and set repository or global options

git-fast-export[1]
Git data exporter

git-fast-import[1]
Backend for fast Git data importers

git-filter-branch[1]
Rewrite branches

git-mergetool[1]
Run merge conflict resolution tools to resolve merge conflicts

git-pack-refs[1]
Pack heads and tags for efficient repository access

git-prune[1]
Prune all unreachable objects from the object database

git-reflog[1]
Manage reflog information

git-remote[1]
Manage set of tracked repositories

git-repack[1]
Pack unpacked objects in a repository

git-replace[1]
Create, list, delete refs to replace objects

Interrogators:

git-annotate[1]
Annotate file lines with commit information

git-blame[1]
Show what revision and author last modified each line of a file

git-bugreport[1]
Collect information for user to file a bug report

git-count-objects[1]
Count unpacked number of objects and their disk consumption

git-difftool[1]
Show changes using common diff tools

git-fsck[1]
Verifies the connectivity and validity of the objects in the database

git-help[1]
Display help information about Git

git-instaweb[1]
Instantly browse your working repository in gitweb

git-merge-tree[1]
Show three-way merge without touching index

git-rerere[1]
Reuse recorded resolution of conflicted merges

git-show-branch[1]
Show branches and their commits

git-verify-commit[1]
Check the GPG signature of commits

git-verify-tag[1]
Check the GPG signature of tags

gitweb[1]
Git web interface (web frontend to Git repositories)

git-whatchanged[1]
Show logs with difference each commit introduces

Interacting with Others
These commands are to interact with foreign SCM and with other people via patch over e-mail.

git-archimport[1]
Import a GNU Arch repository into Git

git-cvsexportcommit[1]
Export a single commit to a CVS checkout

git-cvsimport[1]
Salvage your data out of another SCM people love to hate

git-cvsserver[1]
A CVS server emulator for Git

git-imap-send[1]
Send a collection of patches from stdin to an IMAP folder

git-p4[1]
Import from and submit to Perforce repositories

git-quiltimport[1]
Applies a quilt patchset onto the current branch

git-request-pull[1]
Generates a summary of pending changes

git-send-email[1]
Send a collection of patches as emails

git-svn[1]
Bidirectional operation between a Subversion repository and Git

Reset, restore and revert
There are three commands with similar names: git reset, git restore and git revert.

git-revert[1] is about making a new commit that reverts the changes made by other commits.

git-restore[1] is about restoring files in the working tree from either the index or another commit. This command does not update your branch. The command can also be used to restore files in the index from another commit.

git-reset[1] is about updating your branch, moving the tip in order to add or remove commits from the branch. This operation changes the commit history.

git reset can also be used to restore the index, overlapping with git restore.

The following description divides the low-level commands into commands that manipulate objects (in the repository, index, and working tree), commands that interrogate and compare objects, and commands that move objects and references between repositories.

**Manipulation commands**
git-apply[1]
Apply a patch to files and/or to the index

git-checkout-index[1]
Copy files from the index to the working tree

git-commit-graph[1]
Write and verify Git commit-graph files

git-commit-tree[1]
Create a new commit object

git-hash-object[1]
Compute object ID and optionally creates a blob from a file

git-index-pack[1]
Build pack index file for an existing packed archive

git-merge-file[1]
Run a three-way file merge

git-merge-index[1]
Run a merge for files needing merging

git-multi-pack-index[1]
Write and verify multi-pack-indexes

git-mktag[1]
Creates a tag object with extra validation

git-mktree[1]
Build a tree-object from ls-tree formatted text

git-pack-objects[1]
Create a packed archive of objects

git-prune-packed[1]
Remove extra objects that are already in pack files

git-read-tree[1]
Reads tree information into the index

git-symbolic-ref[1]
Read, modify and delete symbolic refs

git-unpack-objects[1]
Unpack objects from a packed archive

git-update-index[1]
Register file contents in the working tree to the index

git-update-ref[1]
Update the object name stored in a ref safely

git-write-tree[1]
Create a tree object from the current index

Interrogation commands
git-cat-file[1]
Provide content or type and size information for repository objects

git-cherry[1]
Find commits yet to be applied to upstream

git-diff-files[1]
Compares files in the working tree and the index

git-diff-index[1]
Compare a tree to the working tree or index

git-diff-tree[1]
Compares the content and mode of blobs found via two tree objects

git-for-each-ref[1]
Output information on each ref

git-for-each-repo[1]
Run a Git command on a list of repositories

git-get-tar-commit-id[1]
Extract commit ID from an archive created using git-archive

git-ls-files[1]
Show information about files in the index and the working tree

git-ls-remote[1]
List references in a remote repository

git-ls-tree[1]
List the contents of a tree object

git-merge-base[1]
Find as good common ancestors as possible for a merge

git-name-rev[1]
Find symbolic names for given revs

git-pack-redundant[1]
Find redundant pack files

git-rev-list[1]
Lists commit objects in reverse chronological order

git-rev-parse[1]
Pick out and massage parameters

git-show-index[1]
Show packed archive index

git-show-ref[1]
List references in a local repository

git-unpack-file[1]
Creates a temporary file with a blob’s contents

git-var[1]
Show a Git logical variable

git-verify-pack[1]
Validate packed Git archive files

In general, the interrogate commands do not touch the files in the working tree.

Syncing repositories
git-daemon[1]
A really simple server for Git repositories

git-fetch-pack[1]
Receive missing objects from another repository

git-http-backend[1]
Server side implementation of Git over HTTP

git-send-pack[1]
Push objects over Git protocol to another repository

git-update-server-info[1]
Update auxiliary info file to help dumb servers

The following are helper commands used by the above; end users typically do not use them directly.

git-http-fetch[1]
Download from a remote Git repository via HTTP

git-http-push[1]
Push objects over HTTP/DAV to another repository

git-receive-pack[1]
Receive what is pushed into the repository

git-shell[1]
Restricted login shell for Git-only SSH access

git-upload-archive[1]
Send archive back to git-archive

git-upload-pack[1]
Send objects packed back to git-fetch-pack

Internal helper commands
These are internal helper commands used by other commands; end users typically do not use them directly.

git-check-attr[1]
Display gitattributes information

git-check-ignore[1]
Debug gitignore / exclude files

git-check-mailmap[1]
Show canonical names and email addresses of contacts

git-check-ref-format[1]
Ensures that a reference name is well formed

git-column[1]
Display data in columns

git-credential[1]
Retrieve and store user credentials

git-credential-cache[1]
Helper to temporarily store passwords in memory

git-credential-store[1]
Helper to store credentials on disk

git-fmt-merge-msg[1]
Produce a merge commit message

git-interpret-trailers[1]
Add or parse structured information in commit messages

git-mailinfo[1]
Extracts patch and authorship from a single e-mail message

git-mailsplit[1]
Simple UNIX mbox splitter program

git-merge-one-file[1]
The standard helper program to use with git-merge-index

git-patch-id[1]
Compute unique ID for a patch

git-sh-i18n[1]
Git’s i18n setup code for shell scripts

git-sh-setup[1]
Common Git shell script setup code

git-stripspace[1]
Remove unnecessary whitespace

Guides
The following documentation pages are guides about Git concepts.

gitattributes[5]
Defining attributes per path

gitcli[7]
Git command-line interface and conventions

gitcore-tutorial[7]
A Git core tutorial for developers

gitcredentials[7]
Providing usernames and passwords to Git

gitcvs-migration[7]
Git for CVS users

gitdiffcore[7]
Tweaking diff output

giteveryday[7]
A useful minimum set of commands for Everyday Git

gitfaq[7]
Frequently asked questions about using Git

gitglossary[7]
A Git Glossary

githooks[5]
Hooks used by Git

gitignore[5]
Specifies intentionally untracked files to ignore

gitmailmap[5]
Map author/committer names and/or E-Mail addresses

gitmodules[5]
Defining submodule properties

gitnamespaces[7]
Git namespaces

gitremote-helpers[7]
Helper programs to interact with remote repositories

gitrepository-layout[5]
Git Repository Layout

gitrevisions[7]
Specifying revisions and ranges for Git

gitsubmodules[7]
Mounting one repository inside another

gittutorial-2[7]
A tutorial introduction to Git: part two

gittutorial[7]
A tutorial introduction to Git

gitworkflows[7]
An overview of recommended workflows with Git

[Home](https://omaxrali.github.io/Reading-Notes/)
