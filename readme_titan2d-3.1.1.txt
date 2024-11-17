TITAN2D can be installed in user's own directory, but it needs MPI, Python-tk and GRASS already installed in the machine by the root.
GRASS does not need to be run to treat the DEM data given in below item 2) as this DEM data has already been preprocessed, but needs to be run
for preprocessing other new terrain DEM data.

1) To install titan2d, unzip titan2d-mod source code file, go into the uncompressed directory titan-3.1.1, and
   type:
   ./install-titan.sh
   At the prompt, choose "continue without hdf5". 
   (For other installation methods, please refer to tutorial/titan_userguide.pdf)

2) example_vector.tar.gz is a lava flow example DEM map. To run this example, uncompress it in any separate directory
   like </home/user>.  Start preprocessing script "titan_gui.py" in directory titan-3.1.1/bin, and copy parameters
   in file "</home/user>/example/example.readme" to the blank line of the prompted window. When titan_gui.py is finished,
   all necessary files for running this example will be created in directory TEST1. Go to TEST1 and run titan.

3) To run titan correctly one should first read titan_userguide.pdf. This file and other documents about our
   new model as well as treating DEM topography and general slope are placed in directory tutorial.