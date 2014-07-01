# Rob's Scripts Collection

This repository is a collection of simple scripts for general use. They are dsecribed below.

## xkcdpw

![XKCD 936](http://imgs.xkcd.com/comics/password_strength.png)

`xkcdpw` is a simple script to implement the password generation mechanism from [XKCD 936](http://xkcd.com/936/). You must specify a file to use as a word list (note that /usr/share/dict/words is *not* a good choice, as obscure and hard-to-spell words vastly outnumber simple ones). By default, a four-word password is generated, but if you want another number add "-n <N>" to the command line.

