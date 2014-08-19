Introduction
============

Naturalis documentation is made with a couple of tools that might be more or less familiar to developers and probably a bit less familiar to others. That is not to say it is really difficult to contribute to the documentation. This document explains the basics and refers you to the relevant documentation when necessary.

reStructuredText
----------------

The first thing you have to know is that you'll have to write documentation in a markup language called `reStructuredText <http://sphinx-doc.org/rest.html>`_. To `quote <http://docutils.sourceforge.net/rst.html>`_ the makers:

    "reStructuredText is an easy-to-read, what-you-see-is-what-you-get plaintext markup syntax and parser system. It is useful for in-line program documentation (such as Python docstrings), for quickly creating simple web pages, and for standalone documents."

Basically this means you'll write plaintext documents with a simple markup with which you specify the different parts of a text. For example, section headers are written like this::

   This is a header
   ================

reStructuredText is fairly rich (compared to Markdown for example) and allows you to signify things like code blocks (like the one above), tables, footnotes and special blocks like tips, warnings etc.

You might want to start reading the `basic introduction to the syntax <http://sphinx-doc.org/rest.html>`_, or check the `detailed technical specification <http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html>`_.
