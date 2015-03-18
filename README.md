
# Sublime HTML2Jade
A quick way to convert HTML to Jade without leaving Sublime Text 2.

This Package is a direct clone of [JS2Coffee](https://github.com/nibblebot/sublime-js2coffee), replacing the `js2coffee` command with `html2jade`. All accolades and copyrights go to the original packages author.


## Installation

* Install [node](http://nodejs.org/) and [npm](https://npmjs.org/) (html2jade requires these)
* Install [html2jade](https://github.com/donpark/html2jade)
* Install the [Jade Sublime Package](https://github.com/davidrios/jade-tmbundle) for syntax highlighting

then, either

* Install [Package Control](http://wbond.net/sublime_packages/package_control) if you don't already have it.
* `cmd-shift-p` Package Control: Install Package -> HTML2Jade

or

* Clone this repo into your `Packages` directory (**Not Recommended:** cloning will not allow you to update automatically).


## Usage

`cmd-shift-p` html2jade:


The syntax will be automatically set to Jade, and either the current file will be replaced with the Jade convertion, or a new file will be opened containing the conversion (depending on the command you used).




## Bind a Key Combination
**Note:** Out of courtesy, there is no keyboard shortcut set by default.

In `Packages/User/Default (`your OS`).sublime-keymap` add one of the following lines:

* `{ "keys": ["ctrl+shift+j"], "command": "html_jade", "args":{"new_file": true}}`

or

* `{ "keys": ["ctrl+shift+j"], "command": "html_jade", "args":{"new_file": false}}`


## Troubleshooting

If `html2jade` outputs an error message it will show up in Sublime Text's console. There is not always useful context information in these messages, so YMMV.
