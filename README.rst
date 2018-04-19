======================
sphinxcontrib-graphene
======================

**sphinxcontrib-graphene** is a `Sphinx`_ extension to generate `GraphQL`_
API docs from `Graphene-Python`_ Schema objects.

.. code:: bash

   pip install sphinxcontrib-graphene

Usage
=====

Add ``sphinxcontrib-graphene`` to ``extensions`` list attribute in  your Sphinx
``conf.py`` configuration file

.. code:: python

   extensions = [
      ...
      'sphinxcontrib.graphene,
   ]

and use the ``graphene`` directive to render GraphQL documentation for a
`Graphene Schema <http://docs.graphene-python.org/en/latest/types/schema/>`_
object attribute from a Python module.

.. code:: restructuredtext

   .. openapi:: path/to/module/containing/graphene/schema.py

Links
=====

* Source: https://github.com/mojochao/sphinxcontrib-graphene
* Bugs: https://github.com/mojochao/sphinxcontrib-graphene/issues

.. _Sphinx: http://www.sphinx-doc.org/en/master/
.. _GraphQL: http://graphql.org
.. _Graphene-Python: http://graphene-python.org/
