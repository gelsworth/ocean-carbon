Welcome to the *ocean-carbon* Tutorial 
--------------------------------------

This website contains a set of tutorials about how to use `ocean-carbon`_, an open-source, multi-model validation tool that can be used to evaluate the performance of ocean biogeochemical models. The tutorials were written in Python and make use of the `ocean-carbon`_ Python library, a library written specifically for loading, plotting, and analyzing ocean biogeochemical model output and comparing it to ocean carbon observations. 

Additional Resources
--------------------
The `ocean-carbon`_ package uses output from global ocean biogeochemical models at 1-degree spatial resolution and monthly temporal resolution. The package is designed to be benchmark carbon parameters with output from the Goddard Earth System Model - NASA Ocean Biogeochemical Model (GEOS-NOBM) which is released as NetCDF files. If you would like to analyze a suite of ocean biogeochemical parameters including nutrients and chlorophyll, we would recommend the `ILAMB`_ toolboxes.

The `ocean-carbon`_ package used in this tutorial was inspired by the `WeatherBench`_ and `ILAMB`_ toolboxes. 

.. _ocean-carbon : https://github.com/gelsworth/ocean-carbon
.. _WeatherBench : https://github.com/pangeo-data/WeatherBench
.. _ILAMB : https://github.com/rubisco-sfa/ILAMB

Getting Started
---------------

.. toctree::
   :maxdepth: 2
   :caption: Test

   PoseidonNOBM_pCO2_Cflux.ipynb
