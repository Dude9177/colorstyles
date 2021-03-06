# colorstyles
## A huge collection of colors for the web
A bunch of color styles foreground, background, outlines and borders including :hover, :focus and :active

## Install colorstyles

You can get the code a few different ways

Download a zip from this page

Install via bower:
```
bower install colorstyles
```

### Using the css
Simply include the files you want in the head of your html document

```html
<link rel="stylesheet" href="bower_components/colorstyles/dist/colors.min.css">
```

or

```html
<link rel="stylesheet" href="bower_components/colorstyles/dist/extendedColors.min.css">
```

### Use the colordefinitions

#### Foreground

Use the ```fg-*``` prefix to define foreground colors like ```fg-white```.

#### Background

Use the ```bg-*``` prefix to define background colors like ```bg-white```.

#### Outlines

Use the ```ol-*``` prefix to define outline colors like ```ol-white```.

#### Borders

Use the ```bd-*``` prefix to define border colors like ```bd-white```.

#### ```:hover```, ```:focus```, ```:active```

For foreground and borders you can define colors for pseudoclasses like ```bg-hover-white```

### Example

```html
<div class="fg-white bg-blue bg-hover-darkBlue">White text with blue background. On hover the Background changes to dark blue.</div>
```

# Author
[@dude9177](https://github.com/Dude9177)

# License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

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