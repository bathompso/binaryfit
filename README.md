BINOCS (Binary INformation from Open Clusters using SEDs)
=====

BINOCS is a suite of python codes that facilitate binary star detection in open clusters. This code, and the method it implements, is described in Thompson et al. (*in prep*)



Installation
------------
BINOCS code will run under Python versions 2.7.x, as well as Python 3.x

In addition to the default Python modules, BINOCS requires the following modules be installed: 

* NumPy
* SciPy
* Matplotlib
* PyOpenCL

All necessary modules can be installed via `pip`. Once pre-requisites are met, simply add the `binocs/python` folder to your `$PYTHONPATH` variable.



Available Routines
------

The BINOCS code consists of three separate routines, each of which is implemented by a program in the BINOCS root folder:

* `payst` --- handles matching of photometry data files, as well as membership data, into a formatted master catalog
* `makeiso` --- processes downloaded isochrone files into the expected format 
* `binaryfit` --- executes the BINOCS binary detection technique

Descriptions of input, execution, and output of each of the routines is located in files in the `doc` folder.


Publications
-------

Publications use various versions of the BINOCS code. While all versions should produce nearly-exact results, there may be some variation between versions. Publications and their associated tags are listed below:

* *BINOCS I: Radial Migration of Binary Systems in Open Clusters.* Thompson et al. (in prep) - [v2.1](https://github.com/bathompso/BINOCS/releases/tag/v2.1)

