---
layout: page
title: Software
permalink: /software/
---

## Programs and Libraries

### Humour

This little program manipulates a deck of cards I\'ve been working on
creating (details will be linked here once I get a set of rules
together). It\'s in alpha, but it *does* build and has all of the cards
available.

[Github Repo][1]

### libfileio

A shared C++ library for reading and writing to CSV files. I made this
to simplify loading and saving data in my future programs. Useable as
a shared library.

[Github Repo][2]

## Bash Scripts

### mpdburn

Using mostly tools that came stock on Slackware 14.2, this script takes a currently playing mpd playlist and burns it to an audio CD. 

Requires k3b, kdialog, MPC, and Perl.

[Raw Script on GitHub][3]

### ripalbum

In order to automate ripping my Dad's large CD collection for him, I
wrote a script that will accept crude album info (Title of Album,
Album Artist, Year, and Number of Discs) and rip and import the entire
thing with little user interaction.

Requires Beets Music Library, cdparanoia, id3tag, and access to sudo
(for ejecting troublesome drives).

[Raw Script on GitHub][4]

* * *

[1]: https://github.com/cdr255/humour 
[2]: https://github.com/cdr255/libfileio0
[3]: https://github.com/cdr255/scripts/blob/master/bash/mpdburn
[4]: https://github.com/cdr255/scripts/blob/master/bash/ripalbum
