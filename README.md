Clementine, the music collector's edition
=========================================

This is Ville Ranki's fork of Clementine located at:

https://github.com/vranki/Clementine

This fork exists, because i wanted to improve the collection management
features of Clementine. My pull requests were not accepted to upstream 
without explanation, so i decided to fork. Clementine devs are welcome to
import my changes to the upstream version. 

New features
------------

Scanning:
- Abort scanning process (found in the Tools menu)
- Rescan any directory manually from right-click context menu

Tag editor:
- Tagged files are re-scanned and updated to the GUI
- Tagged files are removed from the list (to display progress)
- It is now possible to abort the tagging process




Clementine
==========

Clementine is a modern music player and library organizer for Windows, Linux and Mac OS X.

- Website: http://www.clementine-player.org/
- Github: https://github.com/clementine-player/Clementine
- Buildbot: http://buildbot.clementine-player.org/grid
- Latest developer builds: http://builds.clementine-player.org/

Opening an issue
----------------
### Ask for a new feature

Please:

 * Check if the new feature is not already implemented (Changelog)
 * Check if another person didn't already open an issue
 * If there is already an opened issue there is no need to comment "+1", it won't help. Instead, you can subscribe to the issue to be notified of anything new about it

### Report a bug

Please:
 
 * Try the latest developer build (http://builds.clementine-player.org/) to see if the bug is still present (**Attention**, those builds aren't stable so they might not work well and could sometimes break things like user settings). If it works like a charm even though you see an open issue, please comment on it and explain that the issue has been fixed
 * Check if another person has already opened the same issue to avoid duplicates
 * If there already is an open issue you could comment on it to add precisions about the problem or confirm it
 * In case there isn't, you can open a new issue with an explicit title and as much information as possible (OS, Clementine version, how to reproduce the problem...)
 * Please use http://pastebin.com/ for logs/debug
 
If there are no answers, it doesn't mean we don't care about your feature request/bug. It just means we can't reproduce the bug or haven't had time to implement it :o)

Compiling from source
---------------------

Get the code (if you haven't already):

    git clone https://github.com/clementine-player/Clementine.git && cd Clementine

Compile and install:

    cd bin
    cmake ..
    make -j8
    sudo make install

See the Wiki for more instructions and a list of dependencies:
https://github.com/clementine-player/Clementine/wiki/Compiling-from-Source
