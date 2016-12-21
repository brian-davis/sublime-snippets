# Sublime snippets

## Background
A collection of snippets I have created for Sublime Text 3 to make my programming easier.

## Installation
1. In Sublime Text 3, select `Tools > Developer > New Snippet` from the toolbar.  In the file system
popup, observe the directory where snippets are stored on your system.  On my system (Mac OS),
it is: `~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/snippets/`.
2. clone this repo into a different working directory.
3. `cp` any desired `.sublime-snippet` files into the snippets directory from step 1.
4. Start or restart Sublime Text 3.

## Use
These are the inluded snippets.  To use, type the **trigger text** in the text editing window of
Sublime Text 3 and then the tab key.  The text should populate.  Keep tabbing to reach preset
text insertion points.

### C
Context must be **C**.

* **hw** - boilerplate for a very simple _hello\_world_-style C program.

### Ruby
Context must be **Ruby** or **Ruby on Rails**.

* **class** - boilerplate for a Ruby class.
* **minitest** - boilerplate for a Minitest unit test.

### Ruby ERB
Context must be **HTML(Rails)**

* **%** - expand to a non-printing ERB tag: `<% %>`
* **%=** - expand to a printing ERB tag: `<%= %>`
