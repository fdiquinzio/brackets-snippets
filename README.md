#brackets-snippets [![build status](https://travis-ci.org/zaggino/brackets-snippets.svg?branch=master)](https://travis-ci.org/zaggino/brackets-snippets)

Snippets extension for Brackets

Default shortcut to launch is *Alt-S*

You can go to *Edit -> Trigget code snippet* to open the settings dialog and change the shortcut.

See [CHANGELOG](CHANGELOG.md) for latest news on features/fixes.

Available to install from Brackets inbuilt [extension registry](https://brackets-registry.aboutweb.com/).

###Features
- Create/Update/Delete reusable code snippets (v0.0.1)
- Export/Import code snippets to Gist (v0.0.1)
- Default Snippets support (v0.0.2)
- Loading Snippets from directories (v0.0.2)
- Set cursor position after inserting a snippet with cursor mark ({{!cursor}}) (v0.0.2)
- Support for variables in snippets (v0.0.4)

###Keyboard
- Use `Alt-S` (or your own defined shortcut) to open a snippet widget
- Use `Up` and `Down` arrows to navigate between various snippets
- Use `Enter` key to insert currently selected snippet (if there are any variables, `Enter` will navigate you to the variables you need to fill out first)
- Use `Tab` key to navigate between variables (if there are any empty ones, `Tab` only navigates between empty)
- Use `Esc` key to close the widget any time

###Creating own snippet

![create-snippet-image](docs/images/create-new-snippet.png)
