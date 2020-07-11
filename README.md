# scssSymlinkWatchBug

## Creating the symlinks:

Go into the `symlinkBugTest/src` folder and run two commands:

### Linux:
ln -s ../../realFolder1 link1
ln -s ../../realFolder2 link2

### Windows (PowerShell):
New-Item -ItemType Junction -Target ..\..\realFolder1 link1
New-Item -ItemType Junction -Target ..\..\realFolder2 link2
