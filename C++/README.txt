PolyCARP (Algorithms and Software for Computations with Polygons) 
------------------------------------------------------
Version:  C++
Release: FormalATM-v2.5.5, September 23, 2016
Authors: Anthony Narkawicz, George Hagen
Contact: Cesar A. Munoz (Cesar.A.Munoz@nasa.gov)

Copyright: Copyright (c) 2014 United States Government as represented by 
the National Aeronautics and Space Administration.  No copyright 
is claimed in the United States under Title 17, U.S.Code. All Other 
Rights Reserved.

Introduction
------------
PolyCARP is a package of algorithms, including both their formal
models and software implementations, for computing containment,
collision, resolution, and recovery information for polygons. The
intended applications of PolyCARP are related, but not limited, to
safety critical systems in air traffic management.

Usage Rights
------------

This software is released under the NASA Open Source Agreement,
version 1.3.  The usage agreement is fully described in the file
NASA_Open_Source_Agreement.pdf.  As part of this agreement, you are
requested to email the following information: first and last name;
email address; and affiliation to j.m.maddalon@nasa.gov. This
information will be used for statistical purposes only.

Description of Files
--------------------

README.txt : This file.
src/: Directory of C++ code.
include/: Directory of C++ headers.
lib/: Directory of library file.
doc/: Directory of documentation.
PolycarpExample.cpp: Example application.
Makefile: Unix make file to compile example application.

Compiling example applications
------------------------------

To produce binary files and compile example application
in a Unix environment, type

$ make

Running example applications
----------------------------

To run the example application in a Unix environment, type

$ ./PolycarpExample
