# img-to-ansi
This PHP script converts an image in libgd-supported formats to ANSI text.

It currently only uses 24-bit ANSI colors. I wrote this for my own use and I use iTerm which supports 24-bit colors. Other color sets in ANSI vary depending on the terminal. Only 24-bit colors are truly the same between terminals. The drawback being that a lot of terminals don't support 24-bit color.

## Instructions
Save this script to your computer then run it with: `php img-to-ansi`

You can also make the file executable and run it directly with: `./img-to-ansi`

## Prerequisites
* You'll need to have PHP 7 installed and in your path.
* You'll need a terminal app that supports 24-bit colors.
