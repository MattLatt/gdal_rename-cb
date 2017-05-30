# gdal_rename-cb

This repository contain the Code::Blocks 16.01 project to build the gdal_rename application on linux
Tested on Ubuntu 16.04, with gdal 2.2.0, gcc 5.4.0.

Overview:
------------------------------------------------------------------------------
Simple Code::Blocks 16.01 project to compile the gdal_rename source (https://github.com/MattLatt/gdal_rename)
It load the gdal_rename.cpp in the folder ../gdal_rename/gdal_rename.cpp and all the gdal 2.2.0 includes are relative
to the folder ../gdal-2.2.0/

So to compile you must have the following folder tree

    --gdal_rename\gdal_rename.cpp
    |
    --gdal_renema-cb\gdal_rename.cbp...
    |
    --gdal-2.2.0\...

Ther is also a Visual C++ 2010 workspace linked with GDAL dll in my GDAL_2.2.x_VC repository
here: https://github.com/MattLatt/GDAL_2.2.x_VC   

Authors:
------------------------------------------------------------------------------

* [Mathieu Lattes] (mathieu.lattes@yahoo.fr)

Version:
------------------------------------------------------------------------------


* v0.0.1_20170530-01 : initial version

History:
------------------------------------------------------------------------------
