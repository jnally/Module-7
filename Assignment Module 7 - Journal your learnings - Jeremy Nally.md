# Assignment Module 7 - Journal your learnings
**Name:** Jeremy Nally
**Date:** March 2, 2026

## Chapter 15: Git GUI Tools
Transitioning from the command line to graphical tools makes managing repositories much easier. Chapter 15 highlighted several key tools that can streamline my workflow:
* **Default Tools (`git-gui` & `gitk`):** Great for quick staging, committing, and visualizing branch history and can be opened directly from the terminal.
* **IDE Integration (VS Code):** VS Code's native Source Control tab is incredibly powerful for my Python, React, and Node.js projects, allowing me to see diffs and manage branches directly. I already have some basic experience with it from other coursework.
* **Specialized Clients (GitHub Desktop & GitKraken):** GitHub Desktop offers a clean, modern interface for everyday tasks. GitKraken provides a good-looking, highly visual representation of complex branching and commit histories, which is perfect for understanding deeper project structures.

## Chapter 16: Advanced Git
These commands act as a crucial safety net for development:
* **Reverting:** `git checkout -- <file>` is the fastest way to discard local changes to a specific file.
* **Stashing:** `git stash push` and `git stash pop` allow me to save a dirty working directory when I need to quickly switch branches to fix something urgent.
* **Resetting:** `git reset --hard` permanently wipes out uncommitted changes and resets the branch to a previous state.

## Difficulties & Reflections
The main difficulty will be building the muscle memory to use `git stash` instead of creating messy, temporary commits just to switch branches. I will probably completely avoid using `git reset` so I don't accidentally delete hours of work on my new development projects.
