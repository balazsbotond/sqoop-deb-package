Debian package for Apache Sqoop
===========================

A Debian package for installing Apache Sqoop 1.4.6. Works on Ubuntu.

**Download the latest pre-built release here:**
https://github.com/balazsbotond/sqoop-deb-package/releases

Building the package
--------------------

Clone the repository:

    git clone https://github.com/balazsbotond/sqoop-deb-package.git

Build the package using `dpkg-deb`:

    dpkg-deb --build sqoop_1.4.6-1

This will create a `sqoop_1.4.6-1.deb` file in the current directory.

Installing the package
----------------------

    dpkg -i sqoop_1.4.6-1.deb
    apt-get install -f

