# COLORS-SASS

## Better colors for the web.

View the project page at [http://clrs.cc](http://clrs.cc "Colors: Better colors for the web.")

<div align="center">
  <img src="palette.png"/>
</div>

## What is this?

A simple color palette for the web. Let's be honest, out of the box, the color strings that css provides aren't... the tops.
This is a set of sass/less/stylus/css variables and css classes that can help fix that with just 647B of minified and gzipped css.

(Uncompressed is just 888B)

colors.css provides utilities to apply backgrounds, text-color, border colors for both html and svg elements.

## Install colors.css

You can get the code a few different ways

Download a zip from the github project page

Clone / fork the repo through git
```bash
git clone git@github.com:mrmrs/colors-sass.git
```

Install [through npm](https://www.npmjs.org/package/colors-sass.css)
```bash
npm install --save-dev colors-sass
```

Install the [ruby gem](http://rubygems.org/gems/clrs)
```
gem install clrs
```

### Using the css
Simply copy colors.css to your css directory and include the file like so in the head of your html document

```html
<link rel="stylesheet" href="css/colors.css">
```

## Setup

To install dependencies and convert the sass source files to css run

```bash
npm install && npm start
```

You can customize the colors in ```sass/_variables``` if you'd like to alter any of the 
provided values.

Have fun!

# Author
[MRMRS](http://mrmrs.cc "Adam Morse - Designer + Developer in Hong Kong")


# License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

