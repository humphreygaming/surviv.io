# About
This is a WIP Surviv.io mod. It is a modification of the latest Surviv.io app source. I hope to add these things to it:
* 15x Scope at beggining of game (buggy right now)
* Increasable zoom
* Auto-aim

This is not the normal UserScript, it is not even a UserScript. Do not install modded versions of this as they could break Surviv.io or your Computer. Heed my warnings.

# Features
* Bigger view: 2x Scopes are now 4x Scopes and so on. Some bugs still need to be fixed

# Installation
### Windows, Mac, and Linux
1. Install Telerik Fiddler (https://www.telerik.com/download/fiddler)
2. Download `main.js` from this folder. Copy the full download location.
3. Open Fiddler. Open the AutoResponder tab (it has a lightning bold next to it).
4. Click `Add Rule`. Click the new rule
5. In the rule editor (below the rules) replace `StringToMatch...` with `REGEX:http:\/\/surviv\.io\/js\/app\..*?\.js`
6. Still in the rule editor replace `Local file to return or *Action to exucute` with the `main.js` download location.

Note: there may be slight variation on the OS's I tested this on Windows 10, I have not confirmed it to work on MacOS or LinuxOS.
Note: every time Surviv.io get's updated check here for the latest version. (Current Surviv Version: 4-26-18|Mansion)