Beren Minor's packages for Debian
==================================

This archive provides unofficial *.deb* packages for Debian.

**I do not recommend blindlessly trusting third-party repositories,
but as long as these packages are not yet included in Debian official
archives, the only alternative is to build them yourself from sources.
You'll be able to find the sources of these packages, on my github
account.**

Contents
---------
For now, this repository contains packages for the following software:

- [Dwarf Fortress](http://github.com/berenm/dwarf-fortress)
- [GemRB](http://github.com/berenm/gemrb)

How to install
---------------

```bash
sudo add-apt-repository http://berenm.github.com/debian
wget http://berenm.github.com/debian/berenm.gpg -O - | sudo apt-key add -
sudo aptitude update```