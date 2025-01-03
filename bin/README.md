## Project Information

- Name: Movie Tracker
  - Group: 2
  - Build: 3
  - Major Version: -1
  - Minor Version: 0
  - Patch Version: 3

## Major Version Guide

- -1 : Alpha Version
- 0 : Beta Build

## Dev Information

- app dimension (w,h): 1540, 892
- entertainment status: booleans

  - 1: seen
  - 2: released
  - 3: completed
  - 4: pilot
  - 5: special

## Dictionary

- Module: the ui containing the data from data file (contains info on a single entertainment)
- Module Viewer: the ui that contains all the entertainment modules
- Information Viewer: displays the information from the module

### TODO Implementations

- [ ] the module data viewer was rewritten
  > using FXML to view Module instead of code
- [ ] the UI to view the modules was rewritten

## Version History

### Version -1.0.0 (Dec 6, 2024)

- [x] Project UI built with javafx code.
- [x] data from data.txt was viewable in app.
  > the data from the datafile was read and then put in the app making it viewable.
  > the modules were set in UI with their respective info from datafile

### Version -1.0.1 (Dec 14, 2024)

- [x] some data in the modules were viewable.
  > entertainment type aka Movie, Anime, etc.
  > franchise
  > title

### Version -1.0.2 (Dec 14, 2024)

- [x] the UI was remade from code to using fxml
- [x] MainFrame.java was converted from UI code to Controller for MainFrame.fxml

### Version -1.0.3 (Dec 26, 2024)

- renamed project from "Entertainment Tracker" to "Movie Tracker"
- fixed MainFrame controller from throwing errors making it unable to open the app
  > the commented code was removed. the initialized method was written and two object classes were switched to make them correct.
- created Module controller.
  > error: fxml labels are null

## Features to ADD

- [ ] create tabs for seen, upcoming, watch later

  > get date from user

- [ ] Get date of release and then put the module in watch later category (because it was released)
- [ ] create Settings.fxml and Settings.java as controller

- [ ] create a server and client for this app

  > server should be able to talk to multiple clients

- [ ] create a database using mysql to replace data.txt
- mainframe ui should have

  - [ ] ~~tabs to separate modules~~
  - [ ] search box

- [ ] text template
