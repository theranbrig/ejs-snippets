# EJS Snippets README

This is a basic snippet library for EJS files. EJS can be very useful when used for templating, but it tends to be pretty tedious to write out. I made a library of snippets for writing out EJS in order to make it faster to write. Please let me know if there are issues with the snippets or other ones that could be built. As of now I just have the basics but could add in others if requested.

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions. There you have either the option to show the already installed snippets or install new ones. Search for EJS Snippets and install it.

## Features

**Snippets are found below.**

→ Denotes the `TAB` key.

| Snippet→   | Output                                                                                                  |
| ---------- | ------------------------------------------------------------------------------------------------------- |
| `ejs→`     | `<% %>` - No output tag                                                                                 |
| `ejsout→`  | `<%= %>` - Outputs HTML value                                                                           |
| `ejsesc→`  | `<%- %>` - Outputs unescaped                                                                            |
| `ejscom→`  | `<%# %>` - Comment tag                                                                                  |
| `ejslit→`  | `<%% %>` - Outputs Literal <%                                                                           |
| `ejsinc→`  | `include` statement                                                                                       |
| `ejsfor→`  | `for` Javascript Loop                                                                                             |
| `ejseach→` | `forEach` Javascript Loop                                                                                     |
| `ejsif→`   | `if` Statement with condition                                                                                     |
| `ejselif→` | `else if` Statement - *Middle section only.* Assumes you have already written the first `if` statement. |
| `ejselse→` | `else` Statement - *Middle section only.* Assumes you have already written the first `if` statement.    |

## How can I report an issue or make a request?

The easiest way is to start a git issue, and I will attempt to answer ASAP.

## Source

[GitHub](https://github.com/theranbrig/ejs-snippets)

## Change Log

All notable changes to the "ejs-snippets" extension will be documented in this file.

### [0.5.0]

- Initial release
- Added basic EJS snippets.

### [0.6.0]
- More friendly README
- Changed forEach snippet from `ejsfe` to `ejseach`

### [0.7.0]
- Fixed the `ejselif` statement/

**Enjoy!**
