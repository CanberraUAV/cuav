==========
Installing
==========
Cuav runs on the Python 2.7.x environment. Ensure your system is running the correct version of Python.


Windows
=======

For Windows users, the cuav software installer is found at http://canberrauav.org.au/download/cuav/. The installer
creates links to the software on the start menu.

The changelog (detailing the fixes and enhancements for each version) is found at http://canberrauav.org.au/download/cuav_changelog/

Linux
======

For Debian based systems:

.. code:: bash

    sudo apt-get install python-pip libusb-1.0.0-dev libdc1394-22-dev 
    sudo apt-get install libjpeg-turbo8-dev python-opencv python-wxgtk3.0
    pip install numpy future gooey pytest
    pip install cuav
    
For Fedora based systems:

.. code:: bash

    sudo dnf install python-devel python-opencv wxPython python-pip redhat-rpm-config
    pip install numpy future gooey pytest
    pip install cuav
 
.. note::

    On Raspian, ``libjpeg-turbo8-dev`` is instead named
    as ``libturbojpeg-dev``.

.. note::

    On some older Linux systems, ``python-wxgtk3.0`` may be instead named
    as ``python-wxgtk2.8``.

.. toctree::
    :maxdepth: 1
