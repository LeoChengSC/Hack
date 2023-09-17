# Hack
Ultmate hack here!
- [Edpuzzle](#Edpuzzle_Part)

## Legal or Illgal
- All hacks here are 100% legal.
- You dont have to worry about getting caught or going to jail.
- In-fact, why could I made this hack if it was illegal?

## How To Use
- Requierments
  - PC
  - Chrome
  - Thats all
- Downloads
  - Download [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) extention
  - Open extention
  - Create new costome script
  - Paste the scripe you copied

## Credits
- Edpuzzle
  - LeoChengSC
  - [Google Bard](https://www.bard.google.com)
  - [VS Code](https://code.visualstudio.com/download)

### Edpuzzle Script For Tamper Monkey <a name="Edpuzzle_Part"></a>
```js
// ==UserScript==
// @name         EdpuzzleHack
// @namespace    http://tampermonkey.net/
// @version      1.5
// @description  SchoolSucks
// @author       LeoChengSC
// @match        *://*.edpuzzle.com/*assignments/*
// @icon         https://lh3.googleusercontent.com/a/ACg8ocJBySKqhMqxY32Oxcf876faQ8D5rV8zuqr55XF0t1QulaY=s288-c-no
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    var GitHubScript = document.body.appendChild(document.createElement("script"))
    GitHubScript.src="https://cdn.jsdelivr.net/gh/LeoChengSC/Hack@main/HackScripts/EdpuzzleHackForTamperMonkey.js";
    GitHubScript.remove();
})();
```
