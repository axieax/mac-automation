# mac-automation
Repository containing some of my favourite or most useful automation scripts. Feel free to 

## Open new terminal window at current Finder folder

Sometimes, navigating to a desired folder on Terminal takes quite some effort, especially if it is deeply nested in directories or the folder is already open in Finder. This AppleScript gets the directory of the current Finder window open and opens a new Terminal window to the same directory, allowing you to quickly and easily access commands relevant to that folder. I've personally set this shortcut to be 'Control-T' under `System Preferences > Keyboard > Shortcuts > Services`, so upon using this key combination in Finder, I can quickly run commands such as:
- `code .` (to open my Visual Studio Code IDE to the current folder)
- `code [filename]` (to open and edit an existing file in Visual Studio Code, or create and open a new file which I can immediately start editing in Visual Studio Code - alternatively `touch [filename]` just creates the file)



