Firewood
========

Firewood parses Kindle's "My Clippings.txt" and outputs text files, organized by title.

Useful if you want to be able to skim through the best bits of books you've already read and highlighted. Could also be used with `grep` or some similar search tool to find a particular term in a book.

Usage
-----
###The easy way###
Put the `firewood.app` in the same directory as `My Clippings.txt`, then double-click `firewood.app`. This is an AppleScript that will open a terminal window and run the application.

###The regular way###
Run `make` to create the executable. Put the executable in the same directory as `My Clippings.txt` (this can be found in the Kindle's `documents` directory.)

Run it by executing `./firewood`.

Firewood will create a directory called `Kindle Clippings` and will save all text files there.
