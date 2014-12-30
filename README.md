ColorSuite
==========

![Screenshot 1][Screen1]

*ColorSuite* is an image effect for Unity, which manages multiple color
adjustment tasks in a single component. These tasks are implemented in a single
one-pass shader. In case you dont't use some functions, it automatically strips
out the unused functions from the shader using the multiple shader compilation
technique, and guarantees the best performance in any case.

![Screenshot 2][Screen2]

![Screenshot 3][Screen3]

Features
--------

- Tone mapping ([John Hable's filmic tone mapping operator][Hable])
- White balance (color temperature and green-magenta tint)
- Saturation control
- Tone curves (red, green, blue and RGB-combined)
- Dither (ordered and triangular)

License
-------

Copyright (C) 2014 Keijiro Takahashi

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[Hable]: http://filmicgames.com/archives/75
[Screen1]: http://keijiro.github.io/ColorSuite/screenshot1.png
[Screen2]: http://keijiro.github.io/ColorSuite/screenshot2.png
[Screen3]: http://keijiro.github.io/ColorSuite/screenshot3.png
