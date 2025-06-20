unsplash.py
==========

Installation
------------

**Python 3.8 or higher is required.**

To install the stable version, do the following:

.. code-block:: sh

    # Unix / macOS
    python3 -m pip install "unsplash.py"

    # Windows
    py -m pip install "unsplash.py"


To install the development version, do the following:

.. code-block:: sh

    $ git clone https://github.com/Ombucha/unsplash.py

Make sure you have the latest version of Python installed, or if you prefer, a Python version of 3.8 or greater.

If you have have any other issues feel free to search for duplicates and then create a new issue on GitHub with as much detail as possible. Include the output in your terminal, your OS details and Python version.


Client
-----

.. autoclass:: unsplash.Client
    :members:

Models
-----

.. autoclass:: unsplash.UnsplashObject
    :members:

Functions
----------

.. autofunction:: unsplash.modify_image_url
.. autofunction:: unsplash.get_all_pages
.. autofunction:: unsplash.download_photo
