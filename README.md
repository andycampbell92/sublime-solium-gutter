# Solium Gutter for Sublime Text 3 via node.js
#### [Sublime Text 3](http://www.sublimetext.com/3)
#### [Solium](https://github.com/duaraghav8/Solium)
#### [Node.js download](http://nodejs.org/#download)

## About
Solium Gutter is a Sublime Text 3 plugin inspired by [JSHint Gutter](https://github.com/victorporof/Sublime-JSHint).
It uses [Solium](https://github.com/duaraghav8/Solium) NodeJS library to lint [Solidity](https://github.com/ethereum/solidity) source files.

## Installation
Each OS has a different `Packages` folder required by Sublime Text. Open it via Preferences -> Browse Packages, and copy this repository contents to a new `solium-gutter` folder there.

The shorter way of doing this is:
### Through [Sublime Package Manager](http://wbond.net/sublime_packages/package_control)

* `Ctrl+Shift+P` or `Cmd+Shift+P` in Linux/Windows/OS X
* type `install`, select `Package Control: Install Package`
* type `solium gutter`, select `Solium Gutter`

### Manually
Make sure you use the right Sublime Text folder. For example, on OS X, packages for version 2 are in `~/Library/Application\ Support/Sublime\ Text\ 2`, while version 3 is labeled `~/Library/Application\ Support/Sublime\ Text\ 3`.

These are for Sublime Text 3:

#### Mac
`git clone https://github.com/sey/sublime-solium-gutter.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/solium-gutter`

#### Linux
`git clone https://github.com/sey/sublime-solium-gutter.git ~/.config/sublime-text-3/Packages/solium-gutter`

#### Windows
`git clone https://github.com/sey/sublime-solium-gutter.git "%APPDATA%/Sublime Text 3/Packages/solium-gutter"`

## Usage
Tools -> Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and type `jshint`.

There is no pre-defined keymap for the moment.
