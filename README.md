# Z-Toolbar
A simple productivity toolbar written in C# and WPF.

I have mainly written this tool because i ran out of space in the Windows taskbar and since taskbar icons can be accessed from anywhere with no need to minimize your workspace to access desktop icons (for example),
i created this tool to pin more icons than can be accessed easily from anywhere.

# Features
- The toolbar doesn't occupy any screen real estate because it resides off screen and only shown when the mouse pointer reaches the middle of the top edge of the screen.
- It supports adding files and folders.
- Easy and fast way to remove icons from the list by clicking the `Edit` button.

# Images

## Empty Layout
![Empty Layout](https://i.imgur.com/dOWJyZn.png "Empty Layout")

## Adding Files
![Adding Files](https://i.imgur.com/tGOHaYd.png "Adding Files")

## Adding Files and Folders
![Files and Folders](https://i.imgur.com/BdcsNL6.png "Files and Folders")

## Deleting Items
![Deleting Items](https://i.imgur.com/gOB1hJk.png "Deleting Items")

# Misc
- The app register it self in the windows registery in order to run at startup (if the checkbox was checked).
- Items are saved as a JSON file in the app directory.

# Author
### Hamzi Alsheikh
### Website: [HMZ-Software](https://www.hmz-software.cf)