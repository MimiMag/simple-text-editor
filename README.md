# Simple Text Editor

In this repo, I'll be building a simple text editor guided by [this tutorial](https://viewsourcecode.org/snaptoken/kilo/).

* run `make` to compile the program
* run `./kilo` in your terminal
* press `ctrl + q` to exit the program

## Why raw mode

By default, your terminal starts in *canonical mode*, which means keyboard is only send to a program once the user presses `Enter`. For our editor, we want to process each keypress as it comes in, so we can respond to it immediately. To do so we need to set up the *raw mode*


## ds and cs in printf

`%d` tells `printf()` to format the byte as a decimal number (its ASCII code), and `%c` tells it to write out the byte directly, as a character.


# [Pick up at: Move the cursor](https://viewsourcecode.org/snaptoken/kilo/03.rawInputAndOutput.html)

