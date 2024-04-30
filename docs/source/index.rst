Welcome to SpaGNN's documentation!
===================================

SpaGNN is a flexible framework that utilizes prior knowledge about feature relations to bridge the gap between different feature spaces during unpaired multi-modal data integration.

In the context of single-cell multi-omics, the data modalities correspond to omics layers, e.g., scRNA-seq, scATAC-seq, snmC-seq, etc. "Unpaired" means that different omics layers are not probed in the same single cells, but rather independent samples of (presumably) the same cell population. Prior knowledge consists of prior regulatory interactions between omics features, e.g., RNA genes and ATAC peaks in the case of scRNA-seq and scATAC-seq integration. These interactions are compiled into a guidance graph, and utilized by GLUE to help orient the multi-omics integration.

To get started with ``SpaGNNs``, check out the `installation guide <install.rst>`__ and `tutorials <tutorials.rst>`__.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   install
   tutorials
   data
   api
   release
   dev
   credits

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`












For more details about the SpaGNNs framework, please check out our `publication <https://doi.org/10.1038/s41587-022-01284-4>`__.


**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
