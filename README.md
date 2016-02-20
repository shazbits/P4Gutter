# P4Gutter
----------

Sublime Text 2 plugin to display Perforce diffs in the gutter. See additions, deletions, and modifications.

## Note

This plugin works well alongside of the [Perforce](https://github.com/ericmartel/Sublime-Text-2-Perforce-Plugin) and [Python Flake8 Lint](https://github.com/dreadatour/Flake8Lint) plugins.

### Looks like
![screenshot](screenshot.png)


### Installation
Download this project and place it in your Sublime Text 2 Packages folder (click on <kbd>Preferences</kbd> > <kbd>Browse Packages...</kbd> to open this folder).


### Setup
* You'll need the Perforce command line client ([Perforce Downloads](http://www.perforce.com/downloads/Perforce/Customer)).
* Edit settings from <kbd>Preferences</kbd> > <kbd>Package Settings</kbd> > <kbd>P4Gutter</kbd> > <kbd>Settings - User</kbd>.
* Optionally, create ```.p4_workspace``` files, containing the name of the workspace, in your workspace root directories.


### Usage
#### Gutter Icons
The gutter is updated on file **open** and **save** events.

#### Additional Commands
<kbd>Annotations</kbd><br>

Note: This feature has not been tested in Sublime Text 2.

This opens a new file to display Perforce annotations with change list number and user name prefixed to each line.
Run the ```P4 Annotations``` command from the Sublime command palette;
or you can add a key binding to the ```p4_annotation``` command in your "Key Bindings - User" file, like:

```
    { "keys": ["super+shift+a"], "command": "p4_annotation" }
```


### License
MIT Licensed


### Thanks
All the credit goes to the original author of [P4Gutter for Sublime Text 3](https://github.com/daumiller/P4Gutter).
