# Serubin's DotFiles
 This readme is still be written..
## Installiation

Installing is fairly straight forward, just clone the repo and place it anywhere and use the install script provided.
```bash
git clone https://github.com/Serubin/dotfiles.git && cd dotfiles && source install.sh
```
In order to change the location of the installtion you will have to re-run the install script with ```bash source install.sh ```

## OS Support
* OS X (with brew)
* Debian
* Ubuntu

The install script takes care of all the pre-requists excluding git, bash, and sudo. However this only works with OSX Debian and Ubuntu (for the moment). 

In OS X the script will install brew and all needed components. 

## What's this set up do?

This setup creates a clean bash envirnment with several other applications. Below is each application created and the features added. Of course I encourage you to look through the files to get a better picture of what this will set up for you.

#### Bash
*   Aliases (listed below)
*   Custom PS1 prompt with git integration
*   Functions to make life easy (listed below)

#### git
* Global ignore for mac os x
* Git Aliases (listed below)

#### Vim
* "Smart" features
* Shortcuts
* Line numbers
* Inteligent ignores
* lightline
* YouCompleteMe
* Presistent undo
* Various completion packages

#### Sublime (x server/Desktop Environment)
* Custom Theme - Monkia
* Packages
 * All Autocomplete
 * Apply Syntax
 * BracketHighlighter
 * CodeFormatter
 * SideBarEnhancements
 * Various Completion packages

