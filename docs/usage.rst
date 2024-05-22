Getting Started
===============

.. _installation:

Installation
------------

To use ocean-carbon, first install it using pip:

.. code-block:: console

   (.venv) $ pip install ocean-carbon

Python and Python Packages
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import ocean-carbon
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

