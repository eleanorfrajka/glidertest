Installation
============


PyPI
----

To install the latest released version of this package from PyPI, use:

.. code-block:: sh

    python -m pip install glidertest

Conda
-----

To install from conda, use:

.. code-block:: sh

    conda install --channel conda-forge glidertest

This allows you to import the package into a Python file or notebook with:

.. code-block:: python

    import glidertest

Install for contributing
------------------------

Contributions are welcome! See `the contributing guidelines <https://github.com/OceanGlidersCommunity/glidertest/blob/main/CONTRIBUTING.md>`_ for more details.

To install a local, development version of glidertest, clone the repository, open a terminal in the root directory (next to the ``README.md``) and run these commands:

.. code-block:: sh

    git clone https://github.com/OceanGlidersCommunity/glidertest.git
    cd glidertest
    pip install -r requirements-dev.txt
    pip install -e .

This installs glidertest locally. The ``-e`` ensures that any edits you make in the files will be picked up by scripts that import functions from glidertest.

You can run the example Jupyter notebook by launching JupyterLab with ``jupyter-lab`` and navigating to the ``notebooks`` directory, or in VS Code or another Python GUI.

All new functions should include tests. You can run tests locally and generate a coverage report with:

.. code-block:: sh

    pytest --cov=glidertest --cov-report term-missing tests/

Try to ensure that all the lines of your contribution are covered in the tests.
