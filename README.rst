Beren Minor's packages for Debian
=================================
.. image:: http://stillmaintained.com/berenm/debian.png
    :alt: Still Maintained?
    :target: http://stillmaintained.com/berenm/debian

This archive provides unofficial *.deb* packages for Debian.

.. warning::

  **I do not recommend blindlessly trusting third-party repositories,
  but as long as these packages are not yet included in Debian official
  archives, the only alternative is to build them yourself from sources.
  You'll be able to find the sources of these packages, on my github
  account.**

Contents
---------
For now, this repository contains packages for the following software:

- `Dwarf Fortress`_
- GemRB_

.. _`Dwarf Fortress`: http://github.com/berenm/dwarf-fortress
.. _GemRB: http://github.com/berenm/gemrb

How to install
---------------

.. code:: bash

  sudo add-apt-repository http://berenm.github.com/debian
  wget http://berenm.github.com/debian/berenm.gpg -O - | sudo apt-key add -
  sudo aptitude update
