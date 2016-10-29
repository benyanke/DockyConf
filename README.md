# DockyConf
 
Simple bash setting modification script for Docky on Ubuntu. Add to your $PATH and quickly change docky settings. Still a work in progress. Works by making calls to gconftool-2.

## Current Features
* lock - Lock icons so that they can't be accidentally dragged
 * Easily make sure you don't mess up your layout!
* movemon - Move a dock to a specific display number
 * Handy when you have a laptop and multiple displays. Throw your settings in a bash script, and set up all your docks for a specific monitor setup with one click!
* moveposmon - Change the edge of the display the dock attaches to
 * Move the dock around the edges of the monitor

## Future Features
Create a [GitHub issue](https://github.com/benyanke/DockyConf/issues/new) above to request a new feature!

## Examples

**Unlock icons**
```bash
dockyconf lock 0
```

**Move dock 1 to display 1**
```bash
dockyconf movemon 1 1
```

**Move dock 2 to display 0**
```bash
dockyconf movemon 2 0
```

**Move dock 1 to the top**
```bash
dockyconf movepos 1 top
```
