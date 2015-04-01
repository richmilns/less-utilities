# less-utilities

A collection of useful mixins and libraries that can be installed as a CodeKit Framework for easy inclusion in your local projects

I use these utilities in some of my other projects here on GitHub, so if you get a LESS compilation error in one of those, this is the place to look first :)

## Getting Started

The easiest way to get started is to view [CodeKit's Framework](http://incident57.com/codekit/help.html#codekit-frameworks) settings and then add this as a new framework.

Then from your project's LESS you can simply:
```
// required imports
@import 'less-utilities';
// optional imports
@import 'normalize';
@import 'lesshat3';
@import 'remixins';
```

## What is included?

At heart, LESS Utilities is a small mixin library for LESS which includes mixins for the following (with vendor prefixes where required):

* Clearing and floating
* Assisting with layouts (min-height, centering elements, removing outlines, display:inline-block)
* Styling text elements (hiding text, removing font smoothing, disabling mobile font sizing)

The idea was to provide utilities that complemented many of the existing CSS3 mixin libraries to speed up development.

This project also includes the following third-party code for easy and quick inclusion in your project (credit to all authors):

* [LESSHat](http://lesshat.madebysource.com/) (versions 1-3)
* [LESS Elements](http://lesselements.com/) (version 0.9)
* [Normalize.css](http://necolas.github.io/normalize.css/) (versions 2 & 3)
* [REMixins](https://github.com/christopher-ramirez/remixings)
