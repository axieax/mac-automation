# mac-automation
This repository contains some of my favourite or most useful automation scripts. Feel free to use them for personal use. To install the scripts you want, double-click on the `.workflow` file and follow on-screen commands. If you are not then redirected to the System Preferences window for assigning a shortcut for the script, you can find them under `System Preferences > Keyboard > Shortcuts > Services`.

## Open new terminal window at current Finder folder
Sometimes, navigating to a desired folder on Terminal can take quite some effort, especially if it is already open in Finder or deeply nested in directories. This AppleScript gets the directory of the current Finder window open and opens a new Terminal window to the same directory, allowing you to quickly and easily access commands relevant to that folder. I've personally set this shortcut to be 'Control T', so upon activating this key combination in Finder (shortcut restricted so that the active Window must be Finder), I can quickly run commands such as:
- `code .` (to open my Visual Studio Code IDE to the current folder)
- `code [filename]` (to open and edit an existing file in Visual Studio Code, or create and open a new file which I can immediately start editing in Visual Studio Code - alternatively `touch [filename]` just creates the file)
- `ls` commands combined with different flags to quickly view information about the current directory and its containing files and subdirectories, combining flags such as `-a` for hidden files, `-l` for more information regarding permissions, size and last modification time, and `-R` for recursive listings. 
- `git` commands

Note: on some versions of macOS, Finder will ask for permission to access Terminal when trying to activate the script. Please provide so if prompted.

## Word Count
This simple Bash script displays the number of words and characters in the selected text. I have personally set this shortcut to be 'Command \', so upon activating this key combination in any application with text selected, a window then displays the word and character count of the selected text. 

## Bad Grandmar
This fun but could be useful Bash script quickly toggles settings relevant to Apple's spell checker and auto text completion features. I find this very useful for typing code in Apple Notes, Email or Microsoft Word, which would otherwise face auto capitalisation, spellchecks and unwanted text completion. Since using `Typora` for taking my notes, I've personally used this script less often, but it is handy just in case I need to quickly jot something code down in Apple Notes or Microsoft Word. The four settings toggled are:
- Automatic Spelling Correction
- Automatic Capitalization
- Automatic Period Substitution
- Automatic Text Completion
These settings can be individually and manually toggled under `System Preferences > Keyboard > Text`, although not very convenient, which is why I decided to make this script. I hope you find it helpful!
