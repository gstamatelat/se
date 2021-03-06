.. se documentation master file, created by
   sphinx-quickstart on Sat Jul 31 19:53:38 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

The `se` package
================

.. toctree::
   :hidden:
   :maxdepth: 2

   algorithms
   functions
   classes

.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: Resources

   Github <https://github.com/gstamatelat/se>

The `se` package provides implementations of the SE-A, SE-B and SE-C algorithms. They are algorithms for the generation
of scale-free random graphs via the preferential attachment mechanism. These algorithms differ from traditional graph
generators (like the Barabási–Albert model) as they are exact in terms of the inclusion probabilities of the vertices
during the preferential attachment step as opposed to approximations. The algorithms also run in linear time in respect
to the number of required vertices `n`.

The package contains the single module `se` which is built on top of `NetworkX <https://networkx.org/>`_. This
documentation index separates the module into three components:

#. `Implementations of the core algorithms <algorithms.html>`_.
#. Some `auxiliary functions <functions.html>`_ related to the problem of random sampling or are generic helper utilities.
#. The `RandomSystematicPartitioning class <classes.html>`_, which is the implementation of another partitioning algorithm based on the systematic random sampling design.

------------

:ref:`Reference Index <genindex>`
