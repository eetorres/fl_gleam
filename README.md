fl_gleam
========

This patch 

http://www.fltk.org/str.php?L2672

was merged into the current active development branch FLTK-1.3:

http://www.fltk.org/software.php?VERSION=1.3.x

Get your copy

svn co http://seriss.com/public/fltk/fltk/branches/branch-1.3/ fltk-1.3

And use Gleam outofthebox!

It will stay available here only for refrence purposes:

Gleam 4.3 patch for the FLTK cross-plataform GUI library (www.fltk.org). Add a glossy layout theme to FLTK 1.3.x and 1.3.2. Here the steps of how to use it:

1) get fltk-1.3.2-source.tar.gz from http://fltk.org/software.php (or find a mirror in google)

2) untar it

$ tar -xvzf fltk-1.3.2-source.tar.gz

3) copy the patch file fltk-1.3.2-gleam-4.3.patch to the fltk-1.3.2 directory

4) patch it:

$ patch -p0 < fltk-1.3.2-gleam-4.3.patch

5) then compile it

$ make

6) and run the test

$ ./test/unittests -s gleam

<img src="https://github.com/eetorres/fl_gleam/blob/master/classic.png?raw=true"></img>
![Classic screenshot](https://github.com/eetorres/fl\_gleam/blob/master/classic.png)

<img src="https://github.com/eetorres/fl_gleam/blob/master/gleam.png?raw=true"></img>
![Gleam screenshot](https://github.com/eetorres/fl\_gleam/blob/master/gleam.png "Gleam screenshot")

7) enjoy....

