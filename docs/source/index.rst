.. glidertest documentation master file, created by
   sphinx-quickstart on Tue Oct 29 11:30:19 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to glidertest's documentation!
======================================

Glidertest is a Python package aiming to diagnose possible issues in a glider dataset. The package takes as input data from any glider in `OG1 format <https://github.com/OceanGlidersCommunity/OG-format-user-manual>`_. 

Glidertest has 3 main components:

1. **Tools to diagnose** (see :doc:`glidertest`) issues in your glider data, e.g. data spikes, drift, formatting issues; as well as non-photochecmical quenching and issues with the glider flight model.

2. **Interactive plotting** capability (see :mod:`glidertest.interactive`), enabling a quick browse through data profiles and the ability to zoom in on specific regions of interest.

3. **Summary sheets** (development underway) to produce a summary of an individual glider mission, including basic diagnostics, plots and tables of potential issues.  This provides a way for glider operators to quickly assess the quality of their data and identify potential issues for further investigation.

This package serves solely as a diagnostic tool. It does not provide algorithms to correct potential problems.  It may offer suggestions for where to look for more information on potential issues, e.g. available standard operating procedures (SOPs) or python packages.  In general, we recommend consulting best practice guides like the `Oxygen SOP <https://oceangliderscommunity.github.io/Oxygen_SOP/README.html>`_ and the other OceanGliders SOPs. We also recommend the `GliderTools <https://glidertools.readthedocs.io/en/latest/>`_ Python package for processing and for tools to address some common issues with glider data.

See the **Users Guide** for an example notebook (also in `glidertest/notebooks/demo.ipynb`) to see how to use the various functions with some provided sample data.   Sample data are available from SeaExplorer vehicles in the Baltic and Seagliders in the Labrador Sea.

For recommendations or bug reports, please visit https://github.com/OceanGlidersCommunity/glidertest/issues/new



======================================

.. toctree::
   :maxdepth: 3
   :caption: Getting started

   installation

.. toctree::
   :maxdepth: 3
   :caption: Users guide

   demo-output.ipynb

.. toctree::
   :maxdepth: 3
   :caption: Help and reference

   glidertest 
   GitHub Repo <http://github.com/OceanGlidersCommunity/glidertest>
   references


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
