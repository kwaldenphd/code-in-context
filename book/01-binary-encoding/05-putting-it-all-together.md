# Putting It All Together

In a future lab, we'll spend more time working with image files and encoding. But digital sound represents another example of file formats and encoding in action. The image below shows a 16-bit sound sample.

<p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/Image_19.jpg?raw=true"></p>

Digital sound recordings are created by taking samples of sound at a specific rate. “CD quality” sound is sampled at 44.1 kHz (kilohertz) or 44,100 times per second. This means that 44,100 times per second, a program measures and records the height of a sound’s sound wave and then translates the height to a binary representation in 16-bits or 2 Bytes.

The important take away here is that any piece of information can be represented in bits and then interpreted by the computer. It's not likely you will have to work with the machine at this level. For now, just know that behind the scenes everything that you input into the computer and everything that is outputted is at some point in the process a string of bits.