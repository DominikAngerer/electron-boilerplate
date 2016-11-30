Example Electron
==============
 
Provides cross-platform development environment, which works the same way on OSX, Windows and Linux, and allows you to generate ready for distribution installers of your app for those operating systems.

# Quick start
The only development dependency of this project is [Node.js](https://nodejs.org). So just make sure you have it installed.
Then type few commands known to every Node developer...
```
git clone {thisproject}
cd electron-boilerplate
npm install
npm start
```
... and boom! You have running desktop application on your screen.

# Structure of the project

## Declaring dependencies

There are **two** `package.json` files:

#### 1. `package.json` for development
Sits on path: `electron-boilerplate/package.json`. Here you declare dependencies for your development environment and build scripts. **This file is not distributed with real application!**

Also here you declare the version of Electron runtime you want to use:
```json
"devDependencies": {
  "electron": "1.3.3"
}
```