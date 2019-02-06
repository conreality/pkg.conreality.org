*******************
Conreality Packages
*******************

.. image:: https://img.shields.io/badge/license-Public%20Domain-blue.svg
   :alt: Project license
   :target: https://unlicense.org

.. image:: https://img.shields.io/travis/conreality/pkg.conreality.org/master.svg
   :alt: Travis CI build status
   :target: https://travis-ci.org/conreality/pkg.conreality.org

|

https://wiki.conreality.org/Packages

Linux
=====

`Alpine Linux <https://en.wikipedia.org/wiki/Alpine_Linux>`__
-------------------------------------------------------------

We package for x86-64 (``x86_64``), ARM (``armhf``), and ARM64 (``aarch64``)
on `Alpine Edge <https://wiki.alpinelinux.org/wiki/Edge>`__.

::

   $ echo 'http://pkg.conreality.org/alpine/edge' >> /etc/apk/repositories

   $ wget -P /etc/apk/keys/ http://pkg.conreality.org/alpine/keys/arto@conreality.org-5aa268e7.rsa.pub

   $ apk update

   $ apk search conreality

`Arch Linux <https://en.wikipedia.org/wiki/Arch_Linux>`__
---------------------------------------------------------

We package for x86-64 (``x86_64``) on `Arch
<https://wiki.archlinux.org/>`__.

*(To be written.)*

`Debian <https://en.wikipedia.org/wiki/Debian>`__
-------------------------------------------------

We package for x86-64 (``amd64``) on `Debian 9 ("Stretch")
<https://wiki.debian.org/DebianStretch>`__.

*(To be written.)*

`Ubuntu <https://en.wikipedia.org/wiki/Ubuntu_(operating_system)>`__
--------------------------------------------------------------------

We package for x86-64 (``amd64``) on `Ubuntu 18.04 LTS ("Bionic Beaver")
<https://wiki.ubuntu.com/BionicBeaver>`__.

*(To be written.)*

macOS
=====

`Homebrew <https://en.wikipedia.org/wiki/Homebrew_(package_management_software)>`__
-----------------------------------------------------------------------------------

We `bottle <https://docs.brew.sh/Bottles>`__ for x86-64 (``x86_64``) on
`macOS 10.13 ("High Sierra") <https://en.wikipedia.org/wiki/MacOS_High_Sierra>`__.

*(To be written.)*
