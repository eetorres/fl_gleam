fl_gleam
========

Gleam 4.3 patch for the FLTK cross-plataform GUI library (www.fltk.org). Add a glossy layout theme to FLTK 1.3.x and 1.3.2. 

![Classic screenshot](https://github.com/eetorres/fl\\_gleam/blob/master/classic.png "Classic screenshot")

![Gleam screenshot](https://github.com/eetorres/fl\\_gleam/blob/master/gleam.png "Gleam screenshot")

Here the steps of how to use it:


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

7) enjoy....
