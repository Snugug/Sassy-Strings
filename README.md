# SassyStrings

Here is a [Compass Extension](http://compass-style.org/) providing you all functions you need to manipulate your [Sass](http://sass-lang.com/) strings.

## What's in there? 

* `str-explode`: explodes a string into pieces
* `str-implode`: implodes a list into a string
* `str-last-index`: returns last index of needle in string
* `str-lcfirst`: turns first letter into lower case
* `str-pad`: pads string to match length
* `str-printf`: returns string in a specific format
* `str-repeat`: repeats string n times
* `str-replace`: replaces string with another one
* `str-reverse`: reverses string
* `str-rot`: rotates letters in string
* `str-shuffle`: shuffles letters in string
* `str-split`: splits strings into list
* `str-trim`: removes white spaces before and after string
* `str-ucfirst`: turns first letter into upper case 
* `stringify`: casts to string

As well as default Sass core functions:

* `str-index`
* `str-slice`
* `str-length`
* `str-insert`
* `to-lower-case`
* `to-upper-case`

If you feel like an explorer, you can have a look at the code [here](https://github.com/Team-Sass/Sassy-Strings/tree/master/stylesheets).

## Requirements

* Sass ~> 3.3.0
* Compass ~> 1.0

Some functions depend on other functions. If you include functions individually, make sure to check for these dependencies in their respective docs.