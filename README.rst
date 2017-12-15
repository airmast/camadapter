|version| |license|

camadapterd
===========

``camadapterd`` is the core CamAdapter application.

Installation
============

Using snap
----------

Firstly install `snapd <https://www.ubuntu.com/desktop/snappy>`__ if it is not yet installed::

   sudo apt install snapd

Now you may install the CamAdapter application::

   sudo snap install camadapterd --devmode

Test whether the software installed successfully::

   camadapterd --version

Please refer to `Software User Guide <https://airmast.github.io/camadapter/software/preparation/>`__ for additional information.

From archive
------------

Download the latest version from `Releases section <https://github.com/airmast/camadapterd/releases/latest>`__. Unpack the archive and run the start script::

   tar -xf camadapterd_?.?.?_armhf.tar.gz
   cd camadapterd_armhf
   ./run-camadapterd.sh --version

Activation
==========

You are to buy the activation code by visiting `AirMast CamAdapter page on ugcs.com <https://www.ugcs.com/en/page/airmast-camadapter>`__.

Then please refer to `Activation section of Software User Guide <https://airmast.github.io/camadapter/software/activation/>`__ for additional information.

Further Reading
===============

`Software User Guide → <https://airmast.github.io/camadapter/software/>`__

License
=======

The software is licensed under proprietary license. See `license file <./LICENSE>`__ for details.

.. |version| image:: https://img.shields.io/badge/version-0.5.0-green.svg
   :target: ./CHANGELOG.rst
   :alt: version-badge
.. |license| image:: https://img.shields.io/badge/license-proprietary-green.svg
   :target: ./LICENSE
   :alt: license-badge
