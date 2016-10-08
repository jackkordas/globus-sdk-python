Installation
============

The Globus SDK requires `Python <https://www.python.org/>`_ 2.7+ or 3.3+.
If a supported version of Python is not already installed on your system, see
this `Python installation guide \
<http://docs.python-guide.org/en/latest/starting/installation/>`_.

The simplest way to install the Globus SDK is using the ``pip`` package manager
(https://pypi.python.org/pypi/pip), which is included in most Python
installations:

::

    pip install globus-sdk

This will install the Globus SDK and it's dependencies.

Bleeding edge versions of the Globus SDK can be installed by checking out the
git repository and installing it manually:

::

    git clone https://github.com/globus/globus-sdk-python.git
    cd globus-sdk-python
    python setup.py install
