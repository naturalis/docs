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

A plaintext reStructuredText is already quite readable, but can be processed to a lot of different presentation formats like HTML and PDF.

reStructuredText is fairly rich (compared to Markdown for example) and allows you to signify things like code blocks (like the one above), tables, footnotes and special blocks like tips, warnings etc.

You might want to start reading the `basic introduction to the syntax <http://sphinx-doc.org/rest.html>`_, or check the `detailed technical specification <http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html>`_.

Sphinx
------

As stated above, reStructuredText is pretty readable as plaintext. The plaintext files, the source code so to say, can be transformed into other presentation formats.

Naturalis uses a documentation generator called `Sphinx <http://sphinx-doc.org/index.html>`_ to perform this task. Apart from being able to build all kinds of output formats, Sphinx adds several features to plain reStructuredText. For example, you can easily cross-reference between several reStructuredText files, build table of contents and offer indexes.

As a writer you don't have to deal a lot with Sphinx if you don't want to. There are a couple of exceptions to this rule:

* If you want to make use of the features Sphinx offers. Check the documentation about `Sphinx markup constructs <http://sphinx-doc.org/markup/index.html>`_.
* If you use a local editor and want to preview how Sphinx will process your reStructuredText file. We will add relevant documentation about using Sphinx locally later. In the mean time you can check the general `Sphinx documentation <http://sphinx-doc.org/contents.html>`_.
* If you're an operator and responsible for the builds of the documentation.
