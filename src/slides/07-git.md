# Git
Another everyday tool — `git`. Let's add some hacky aliases to provide more awesomeness.
+ [Git aliases](https://github.com/8kto/dev-scritps/blob/master/env/git/aliases.md)

*Demonstration*


---
**Side note**: Use `gc filename` for quick commit


---
# Some common use cases
Described in [this file](https://github.com/8kto/dev-scritps/blob/master/git/git-commands.md).
+ Remove file from the history
+ Add remote + Show remote repos info
+ Find removed file in history
+ Undo a commit and redo
+ Remove files from the history
+ etc.


---
# Git hooks

**What are Git hooks?**

Git hooks are scripts that Git executes before or after events such as: commit, push, and receive (pull). 
Git hooks are a built-in feature - no need to download anything. Git hooks are run locally.


---
Some example hook scripts include:
+ `pre-commit`: Check the commit message for spelling errors.
+ `pre-receive`: Enforce project coding standards.
+ `post-commit`: Email/SMS team members of a new commit.
+ `post-receive`: Push the code to production.

Check [https://githooks.com](https://githooks.com) for more info.


---
# Git hook example: 
[Add a ticket no in the commit message](https://github.com/8kto/dev-scritps/blob/master/bash/git/hooks/prepare-commit-msg)


---
# Committing code
Why `vim` on commit:
+ I use git in a command line, so it is more natural and saves an additional `Alt+Tab` for switching into IDE or an external GUI tool
+ it ables you to autocomplete words __out of the box__.


---
Another small script eases tedious committing of not-so-important files. 
+ [Script for committing snaps etc.](https://github.com/8kto/dev-scritps/blob/master/bash/git/commit-test-artifacts.sh)


---
# How it works
<video controls autoplay>
  <source src="semantic-commits.mkv" type="video/mp4">
  Your browser does not support the video tag.
</video>

