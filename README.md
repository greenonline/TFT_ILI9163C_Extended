# TFT_ILI9163C_Extended
Extends the TFT_ILI9163C Arduino library to provide cursor positioning using character size, as well as pixels

Inherits	ILI9163C - A fast SPI driver for TFT that use Ilitek ILI9163C.

TFT_ILI9163C_Extended

This library extends the [TFT_ILI9163C](https://github.com/sumotoy/TFT_ILI9163C) library by adding an additional method `setCursorChar()`, which allows the user to specify the cursor's position as if the display were character sized cursor based (6 pixels x 9 pixels), rather than pixels. 

It is still possible to position the cursor, by pixel, as before, using the `setCursor()` method.

Please see also the [ILI9163C_Extended_Char](https://github.com/greenonline/TFT_ILI9163C_Extended_Char) library

Please note that this TFT_ILI9163C_Extended library is somewhat redundant as the [ILI9163C_Extended_Char](https://github.com/greenonline/TFT_ILI9163C_Extended_Char) library, now, also supports *both* pixel and character resolution cursor placement.
