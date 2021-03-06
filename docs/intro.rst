Introduction
============

The **cluster-lensing** project contains tools for calculating properties and weak lensing profiles of galaxy clusters. It includes cluster mass-richness and mass-concentration scaling relations, and NFW halo profiles for weak lensing shear, the differential surface mass density :math:`\Delta\Sigma(r)`, and for magnification, :math:`\Sigma(r)`. Optionally the calculation will include the effects of cluster miscentering offsets.

This framework calculates properties and profiles for every *individual* cluster, storing the data in tabular form. This is useful for fitting measured stacked weak lensing profiles, e.g. when you want to account for the full redshift, mass, and/or centroid offset distributions, and avoid fitting a single average mass at a single effective redshift.

Installation
----------
You can install this package by running:

.. code:: bash

	  \$ pip install cluster-lensing


Upgrade to the newest version by running:

.. code:: bash

	  \$ pip install cluster-lensing --upgrade


Currently, **cluster-lensing** runs on Python 2.7, 3.4, and 3.5, and its dependencies include numpy, scipy, astropy, and pandas.
	  
	  
Support
--------
If you are having trouble using these tools, or have any questions, please don't hesitate to contact the author at jesford[at]uw.edu

License
--------
This project is licensed under the MIT license.
