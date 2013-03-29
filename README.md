fl_gleam
========

Gleam 4.3 patch for the fltk-1.3.2. Add a glossy layout theme to FLTK 1.3.x and 1.3.2. Here the steps of how to use it:

1) get fltk-1.3.2-source.tar.gz

2) untar it

$ tar -xvzf fltk-1.3.2-source.tar.gz

3) copy the patch file fltk-1.3.2-gleam-4.3.patch to the fltk-1.3.2 directory

4) patch it:

$ patch -p0 < fltk-1.3.2-gleam-4.3.patch

5) then compile it with make and run the example:

$ ./test/gleam

6) enjoy....
