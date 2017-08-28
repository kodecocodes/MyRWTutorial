raywenderlich.com Sample App
---
This project is a barebones Xcode 9 application that sets up some of the basics according to standards for raywenderlich.com tutorial sample projects. Such things include:

- Sets the tab width to 2 spaces throughout the project
- Removes some cruft from default files (primarily AppDelegate)
- Removes the default ViewController from the project and Main.storyboard
- Has the LaunchScreen.xib and RW app icons already set up
- Has the correct company name, bundle identifier, and code signing definitions (none)
- Defaults new files to use the correct copyright information

## How To Use This
First, download MyRWTutorial.zip from this repo and use that. Tutorial sample projects should not include a git repo, so *please do not* clone this repo and then start making modifications as the sample project.

After downloading and unzipping the skeleton project, several pieces should be changed to unique values such that they are relevant to the tutorial under development, including:

- Select project in project navigator and rename the project
	- Xcode will prompt to rename targets and other metafiles as well - select all of them
- Change the bundle identifier
- Change the scheme name
- Rename the top-level directory (the one that contains the .xcodeproj file)

## Credits
Huge props to Scott Berrevoets for coming up with this idea and creating the project, and to Richard Critz for developing the FILEHEADER macro to automatically set the copyright.
