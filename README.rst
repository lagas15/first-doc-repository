Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/


install sphinx
pip install sphinx-rtd-theme

documentation for multiple git repositories
https://fmarco76.github.io/git%20and%20related%20services/readthedocs

- cd docs/source
- git submodule add https://github.com/lagas15/second-doc-repository-
- setup branch in .gitmodules
- git submodule update --remote
- update docs/source/index.rst ex: second-doc-repository-/docs/sphinx/index
