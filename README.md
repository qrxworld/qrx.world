# QRx.world

QRx.world is a serverless, generative Operating System

Inspired by IBM's Plan 9 decentralized filesystem, it uses IndexedDB and isomorphic-git to help you instantly spin up networked Linux-like terminals that uses the browser as the graphical layer. It uses the URL as a prompting interface, matching /url/paths/ to the filesystem directories with the ability to ?run='code on load' or ?prompt='an llm to create or update the filesystem'

By using the URL as a dynamic coding and generative prompting interface, this system enables the use of "Agentic QR Codes", or QR Codes that once scanned can bootstrap entire metaverses

# Dependencies
- [xterm.js](https://github.com/xtermjs/xterm.js) - Used to create the terminal emulator interface
- [bash-parser](https://github.com/vorpaljs/bash-parser) - Used to implement Bash without needing to emulate Linux
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Provides a versioned syncing protocol
- [lightning-fs](https://github.com/isomorphic-git/lightning-fs) - Converts IndexedDB into a filesystem




=============================



# Design
## `/index.html`
[ ] Simple full screen xterm component (use `/lib/xterm.js` and `/lib/xterm.css`)
[ ] Use import maps and modules
[ ] Simple ability to type into the terminal (no need to impelment anything yet)
[ ] The entry point is `/system/kernal.js`
[ ] Other dependencies are `/lib/isomorphic-git.js` and `/lib/lighting-fs.js`
## `/system/kernal.js`
## `/system/parser.js`
## `/system/interpreter.js`
## `/system/event/index.js`
## `/system/event/input.js`
## `/system/event/enter.js`
## `/system/event/backspace.js`
## `/system/event/printable.js`
## `/system/command/pwd.js`
## `/system/command/mkdir.js`
## `/system/command/cd.js`
## `/system/command/ls.js`



=============================



# Inspirations
- v86 emulator
- j0rk1 emulator
- browser-shell
- IBM's Plan 9 decentralized filesystem
