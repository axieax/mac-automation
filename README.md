# mac-automation
Repository containing some of my favourite or most useful automation scripts. Feel free to 

## Open new terminal window at current Finder folder
Sometimes, navigating to a desired folder on Terminal can take quite some effort, especially if it is deeply nested in directories or the folder is already open in Finder. This AppleScript gets the directory of the current Finder window open and opens a new Terminal window to the same directory, allowing you to quickly and easily access commands relevant to that folder. I've personally set this shortcut to be 'Control-T' under `System Preferences > Keyboard > Shortcuts > Services`, so upon activating this key combination in Finder (shortcut restricted to the Finder app), I can quickly run commands such as:
- `code .` (to open my Visual Studio Code IDE to the current folder)
- `code [filename]` (to open and edit an existing file in Visual Studio Code, or create and open a new file which I can immediately start editing in Visual Studio Code - alternatively `touch [filename]` just creates the file)
- `ls` commands combined with different flags to quickly view information about the current directory and its containing files and subdirectories, combining flags such as `-a` for hidden files, `-l` for more information regarding permissions, size and last modification time, and `-R` for recursive listings. 
- `git` commands

## 

