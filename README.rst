======================
sphinxcontrib-graphene
======================

**sphinxcontrib-graphene** is a `Sphinx`_ extension to generate [GraphQL](https://graphql.org)
API docs from [Graphene Python](https://graphene-python.org) schema objects.

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
[Graphene Schema](http://docs.graphene-python.org/en/latest/types/schema/)
object attribute from a Python module.

.. code:: restructuredtext

   .. openapi:: path/to/module/containing/graphene/schema.py


Links
=====

* Source: https://github.com/mojochao/sphinxcontrib-graphene
* Bugs: https://github.com/mojochao/sphinxcontrib-graphene/issues


.. _Sphinx: https://sphinx.pocoo.org/
.. _GraphQL: https://graphql.org
