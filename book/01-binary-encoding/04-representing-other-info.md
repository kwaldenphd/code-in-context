# Representing Other Information in Binary

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
  <td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=fabb1a9f-de9e-4bcd-94b4-aef400c1a6c9">Representing Color</a></td>
  </tr>
  </table>

The end of the "Encoding Schema" lecture mentioned how binary numbers are also used to represent things other than numbers, text, or characters.

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Bit_Comparison.png?raw=true" width="500"></p>

What about color? If we use a single byte or 8-bits to represent color, we can represent a total of 256 different colors. However, we perceive a much wider range of colors, so to extend the palette we can represent colors using more bits. 

<fig>
 <p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Image_13.png?raw=true"></p>
 <p align="center"><figcaption>Image from http://i.imgur.com/UqHhN.png</figcaption></p>
 </fig>

Consider the difference between the color palette on old video game systems as compared to what you see on your computer screen today. Mario is a great example. The original Nintendo used 8-bit color, but Super Nintendo used 16-bit color giving a wider range of colors to represent the graphics in the game.

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Hot_Air_Balloons.png?raw=true" width="500"></p>

In 8-bit color, each color is represented in 8-bits or 1 Byte giving a color palette of 256 colors.  16-bit color increases the number of colors in the palette by a factor of two, representing over 65,000 different colors by using 16-bits or 2 Bytes to represent each color (256 x 256 = 65,536). 

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Image_17.png?raw=true" height="500"></p>

As with text encoding standards, there are many different color encoding schemas. We can represent color using discrete values for the primary colors red, green, and blue.

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Color_Table.png?raw=true" width="500"></p>

An `RGB` (red-green-blue) color system can be represented using hex or decimal values.

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Image_15.png?raw=true" height="500"></p>

The Mario example featured 8-bit and 16-bit color. If you've ever seen Red-Green-Blue color sliders, you've seen a 3 byte (24-bit) color system in action.

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSfJMHhYmWaqMo7_Zl2o-RLVwpDVzPDAzSSr2egZdlGjGTf__A/viewform?usp=sf_link">Representing Color Comprehension Check</a></td>
  </tr>
  </table>

## Key Concepts

**Color depth**
- "Color depth, also known as bit depth, is either the number of bits used to indicate the color of a single pixel, or the number of bits used for each color component of a single pixel. Color depth expresses the precision with which the amount of each primary can be expressed; the other aspect is how broad a range of colors can be expressed (the gamut). The definition of both color precision and gamut is accomplished with a color encoding specification which assigns a digital code value to a location in a color space" ([Wikipedia](https://en.wikipedia.org/wiki/Color_depth))

**Hexadecimal (hex)**
- "In mathematics and computing, hexadecimal (also base 16, or hex) is a positional system that represents numbers using a base of 16. Unlike the common way of representing numbers with ten symbols, it uses sixteen distinct symbols, most often the symbols ‘0’–’9’ to represent values zero to nine, and ‘A’–’F’ (or alternatively ‘a’–’f’) to represent values ten to fifteen. Hexadecimal numerals are widely used by computer system designers and programmers, as they provide a human-friendly representation of binary-coded values. Each hexadecimal digit represents four binary digits…For example, a single byte can have values ranging from 00000000 to 11111111 in binary form, which can be conveniently represented as 00 to FF in hexadecimal" ([Wikipedia](https://en.wikipedia.org/wiki/Hexadecimal))

**RGB color model**
- "The RGB color model is an additive color model in which the red, green, and blue primary colors of light are added together in various ways to reproduce a broad array of colors. The name of the model comes from the initials of the three additive primary colors, red, green, and blue. The main purpose of the RGB color model is for the sensing, representation, and display of images in electronic systems, such as televisions and computers" ([Wikipedia](https://en.wikipedia.org/wiki/RGB_color_model))

[Click here](https://github.com/kwaldenphd/bits-bytes/blob/main/key-concepts.md) for the full list of key concepts and definitions for this lab.

## Application

Q4: How would the colors Magenta, Cyan, and Yellow be represented in binary, hex, and decimal? 
- [RGB Color Table](http://www.rapidtables.com/web/color/RGB_Color.htm)