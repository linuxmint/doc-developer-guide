Linux Mint Developer Guide
============================

This document can be read at http://linuxmint-developer-guide.readthedocs.io.

The docs are written in `reStructuredText <http://www.sphinx-doc.org/rest.html>`_.

Build:
------

.. image:: https://readthedocs.org/projects/linuxmint-developer-guide/badge/?version=latest
    :target: http://linuxmint-developer-guide.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status


To build locally install ``python-sphinx``

```
sudo apt-get install python3-sphinx
```
If you don't ``python`` installed, it will install for you.

after that you need to install ``pip``

```
sudo apt install python3-pip
```

and using ``pip3`` you will install the 

```
pip3 install sphinx sphinx_rtd_them
```

to finally  run ``make html`` in the ``docs`` directory.


Resources:
----------

* https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html
* http://www.sphinx-doc.org/en/stable/markup/inline.html
* http://www.writethedocs.org/guide/
* https://developers.google.com/style/highlights

License:
--------

.. image:: https://img.shields.io/badge/code-GPLv3-blue.svg
    :target: https://www.gnu.org/licenses/gpl-3.0.en.html
    :alt: Code GPLv3

.. image:: https://img.shields.io/badge/documentation-CC%20BY--ND-lightgrey.svg
    :target: https://creativecommons.org/licenses/by-nd/4.0/
    :alt: Documentation CC BY-ND

.. image:: https://img.shields.io/badge/screenshots-CC0-ff69b4.svg
    :target: https://creativecommons.org/publicdomain/zero/1.0/
    :alt: Screenshots CC0

