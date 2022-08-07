Extra scripts for pbuilder-dist
===============================

This repository contains several scripts that I found useful when
working with Ubuntu packages:

pde-local
---------

This is a wrapper for pbuilder-dist that automates the workflow
of using pbuilder-dist to incrementally build mutually-dependent packages
that are not a part of a distribution.

update-overrides
----------------

Runs lintian, parses its otuput and updates the lintian-overrides files in
debian/.

There is no explicit installation, these are standalone Perl scripts with
a perldoc. Run "perldoc <script>" to see basic documentation.
