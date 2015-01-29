# Platonic Font

Originally forked from Ionic project's font, which can be found here: http://ionicons.com

## Getting Started

You can install.
     $ bower install platonic-font



## Build Instructions

This repo already comes with all the files built and ready to go, but can also build the fonts from the source. Requires Python, FontForge and Sass:

1) Install FontForge, which is the program that creates the font files from the SVG files:

    $ brew install fontforge ttfautohint

2) Install [Sass](http://sass-lang.com/)

    $ gem install sass

3) Add or subtract files from the `src/` folder you'd like to be apart of the font files.

4) Modify any settings in the `builder/manifest.json` file. You can change the name of the font-family and CSS classname prefix.

5) Run the build command:

    python ./builder/generate.py


## License

Ionicons is licensed under the [MIT license](http://opensource.org/licenses/MIT).
