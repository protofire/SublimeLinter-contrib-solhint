SublimeLinter-contrib-solhint
=========================

[![Build Status](https://travis-ci.org/idrabenia/SublimeLinter-contrib-solhint.svg?branch=master)](https://travis-ci.org/idrabenia/SublimeLinter-contrib-solhint)

This linter plugin for [SublimeLinter](http://sublimelinter.readthedocs.org) provides an interface to [solhint](https://github.com/protofire/solhint). It will be used with files that have the "Solidity" syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here](http://sublimelinter.readthedocs.org/en/latest/installation.html).

### Linter installation
Before installing this plugin, you must ensure that `solhint` is installed on your system. To install `solhint` need to execute next command `npm install -g solhint`. Node.js and NPM must be preinstalled.

### Linter configuration
If you need custom rules configuration - you may run command `solhint init-config` in root folder of your project. After that file `.solhint.json` will be created. You may customize configuration rules in this file.


### Plugin installation
Please use [Package Control](https://sublime.wbond.net/installation) to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

2. When the plugin list appears, type `solhint`. Among the entries you should see `SublimeLinter-contrib-solhint`. If that entry is not highlighted, use the keyboard or mouse to select it.

## Settings
For general information on how SublimeLinter works with settings, please see [Settings](http://sublimelinter.readthedocs.org/en/latest/settings.html). For information on generic linter settings, please see [Linter Settings](http://sublimelinter.readthedocs.org/en/latest/linter_settings.html).

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient.  ;-)

Please note that modifications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
