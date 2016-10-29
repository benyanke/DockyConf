# DockyConf
 
Simple bash setting modification script for Docky on Ubuntu. Add to your $PATH and quickly change docky settings. Still a work in progress.

## Current Features
* lock - Lock icons so that they can't be accidentally dragged
 * Easily make sure you don't mess up your layout!
* move - Move a dock to a specific display number
 * Handy when you have a laptop and multiple displays. Throw your settings in a bash script, and set up all your docks for a specific monitor setup with one click!

## Future Features
Create a [GitHub issue](https://github.com/benyanke/DockyConf/issues/new) above to request a new feature!

## Examples

**Unlock icons**
```bash
dockyconf lock 0
```

**Move dock 1 to display 1**
```bash
dockyconf move 1 1
```

**Move dock 2 to display 0**
```bash
dockyconf move 2 0
```
