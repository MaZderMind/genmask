# Linux Kernel GENMASK Calculator

Have you ever wanted to use the `GENMASK` or `GENMASK_ULL` macros from the linux kernels [bits.h](https://github.com/torvalds/linux/blob/master/include/linux/bits.h) file? Yeah, me neither, but when working with hardware drivers handling bitmasks is quite common when extracting or changing certain bits in registers and depending on where you look and who you ask the use of the `GENMASK` macro-family is sometimes prefered over good old `0xffc` hex literals.

However I found the specific meaning of the `h` and `l` parameter of these macros to be, let's say, under-document and not obvious, so I wrote a small online calculator that helps me out: https://mazdermind.de/genmask/ and I hope it will also help you.

That's it, good luck with your driver and have fun tinkering around.
