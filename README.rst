package_name: Template for Python packages
==========================================


Getting started
===============

To get started, make sure you have the necessary permissions and clone the repository:

.. code-block:: bash

   git clone 
   cd leap

Working with Poetry
====================

To install Poetry, run the following command in the terminal:

.. code-block:: bash

   curl -sSL https://install.python-poetry.org | python3 -

Activate the Poetry shell and install the dependencies:

.. code-block:: bash

   poetry shell
   poetry install

To add an additional package to the project, use the add command. For example:

.. code-block:: bash

   poetry add numpy

To run tests, use the following command:

.. code-block:: bash

    pytest .

The tests code are located in the folder package_name/tests.


Documentation
-------------

Check the sphynx documentation in the folder doc.

TODOs
-----
