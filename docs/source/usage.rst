Usage
=====

.. _installation:

Installation
------------

To use test, first install it using pip:

.. code-block:: console

   (.venv) $ pip install test

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``test.get_random_ingredients()`` function:

.. autofunction:: test.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`test.get_random_ingredients`
will raise an exception.

.. autoexception:: test.InvalidKindError

For example:

>>> import test
>>> test.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

