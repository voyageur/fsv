# fsv

fsv (pronounced eff-ess-vee) is a file system visualizer in cyberspace. It lays out files and directories in three dimensions, geometrically representing the file system hierarchy to allow visual overview and analysis. fsv can visualize a modest home directory, a workstation's hard drive, or any arbitrarily large collection of files, limited only by the host computer's memory and graphics hardware.

Two different 3D representation schemes are offered:

* **MapV view**. This represents files and directories as rectangular blocks, all of equal height, and each with area proportional to the size of the corresponding file. Everything is laid out on top of its parent directory, somewhat like a Venn diagram in 3D. In the sample at left, the yellow blocks are regular files, and the grey blocks underlying them are directories. The root directory is the block at the bottom.
* **TreeV view**. Built around a more conventional tree/leaf paradigm, this view represents directories as interconnected platforms, with leaves (files et al.) sitting on top. Everything is arranged concentrically, with the root directory closest to the center and subdirectories farther out. The leaf blocks all have the same footprint, and vary in height according to the corresponding file size.

fsv combines either of these 3D views with a standard 2D directory tree / file list interface, offering the best of both viewing paradigms. Directories can be expanded (shown) and collapsed (hidden) at will, allowing as much or as little of the file system to be visible at any given time.

More fsv screen shots are available [here](http://fsv.sourceforge.net/screenshots/).

fsv was partly inspired by fsn, the experimental [3D File System Navigator](http://www.sgi.com/fun/freeware/3d_navigator.html) developed some time ago by [Silicon Graphics](http://www.sgi.com/). This program figured prominently in a scene from Steven Spielburg's hit film, [Jurassic Park](http://us.imdb.com/Title?0107290).

## Origin 
This is a git mirror of last sources (0.9) from http://fsv.sourceforge.net/, with merged patches from https://bitbucket.org/legoscia/fsv
