# Git & GitHub


____________________________________

# Gitbook

- a command line application (may be used to build Git pages)
- takes everything in markdown, converts to html and serves it
- reads from file "Summary.md" to build the menu
- has a specific format/html template (may be modified but... why...?)
- doc folder is where the build (with converted htmls) are stored
- summary.md are the gitbook compiler instructions

# Commands

- [Git commands](https://github.com/MarianaCasellaDosSantos/My-Elewa-Study-Journal/blob/master/concepts/CommandLine.md/#git)

# Git

- language that works underlying in your computer folder structure. It decides there, in the OS, in which branch you are

- site with tutorial exercises https://learngitbranching.js.org/

*  Merging:
- will add the branch you want to merge (pull) into the current branch
- will detect conflicts and warn about them: a conflict means two different pieces of content in the same file in the SAME LINE (different content in different lines of the same file are not conflicts!)
- command = Git merge name-of-branch-being-pulled-into-current
- merge conflicts will be 'logged'/saved in the commit three

* Multiple remote repositories
- A given directory in my computer may be connected to more than one remote repositories. For that they are assigned different names. "origin" is the default name given by GitHub. In order to add an extra repository use git add remote + nameofnewrepository + url for cloning