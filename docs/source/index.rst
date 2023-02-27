Welcome to SVPV's documentation!
===================================

**SVPV** is a web tool that allows the user to visualize the colocalization of structural variants (SVs) and single nucleotide polymorphisms(SNPs).

There are two main ways the visualization can be displayed:
1. Selection of phenotype:
* The plot will be against the p-value found in the GWAS Catalog.
* The plot will display all SNPs in the GWAS Catalog and highlight the SNPs associated with the phenotype chosen.
* The SNPs will be highlighted based on the R\ :sup:`2` colocalization value with the SV selected.
* The size of the highted SNPs will be based on the D' colocalization value with the SV selected.

2. Without the selection of phenotype:
* The plot will be against the R\ :sup:`2` colocalization value with the SV selected.
* The plot will display all SNPs available in the colocalization dataset.
* The SNPs will be sized based on the D' colocalization value.
* The SNPs in blue are also found in GWAS catalog while the SNPs in black are not.


Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
