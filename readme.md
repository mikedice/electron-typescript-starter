TypeScript-Electron-VisualStudio Code
=====================================

This is a starter project I use to bootstrap an Electron project using the TypeScript language and Visual Studio Code as the editor. 

Many thanks to Dave M Bush and his blog entry at https://blog.dmbcllc.com/typescript-and-electron-the-right-way/. I used this excellent resource to learn the core things I needed to get this bootstrap working. Thanks man!

This projects assumes you have set up some basic stuff globally in your dev environment
* Install Visual Studio Code. Right now I'm using 1.13.1 on OSX 10.12.5
* Install NodeJS. I install it globally on my dev machine. Right now I'm using nodejs v6.11.0 npm version 3.10.10
* Use NPM to install TypeScript. I install it globally `npm install -g typescript`
* Use NPM to install Electron. I install it globally `npm install -g electron`
* Use NPM to install Typings. I install it globally `npm install -g typings`

To get things going
* Clone this repo
* In the root of the project run `typings install` to install the typings for electron and node
* In VSCode command+shift+B to build. The output goes into the 'app' subdirectory.
* In VSCode you can start the debugger now and launch the app under the debugger

Thats all I have so far. Hope it helps!

Mike (mikedice417@hotmail.com)