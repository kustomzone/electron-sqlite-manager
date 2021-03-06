# SQLite database manager built around Electron

## Overview
A fairly simple and straightforward manager for SQLite3 databases, which:
* creates and opens databases
* creates, displays and alters tables
* searches tables through incremental search
* has a built-in SQL console
* only uses JQuery & JQuery-UI as extra requisites

## Screenshots
![Electron SQLite manager](https://raw.githubusercontent.com/petru-dimitriu/electron-sqlite-manager/master/screen/screen1.PNG)
![Electron SQLite manager](https://raw.githubusercontent.com/petru-dimitriu/electron-sqlite-manager/master/screen/screen2.png)

## Installing
Due to current SQLite3 & Electron.js compatibility issues, installing the app via a plain `npm install` command is currently *not* enough for it to work. 

For Windows x64 builds, I have included a batch file, `install.bat`, which can be run to get everything set up. Be sure to tweak it, if necessary.