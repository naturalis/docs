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

As stated above, reStructuredText is already pretty readable as plaintext. For readers of the documentation we'd like to present something nicer though. Luckily, the plaintext files, the source code so to say, can be transformed into other presentation formats.

Naturalis uses a documentation generator called `Sphinx <http://sphinx-doc.org/index.html>`_ to perform this task. Apart from being able to build all kinds of output formats, Sphinx adds several features to reStructuredText. For example, you can easily cross-reference between several reStructuredText files, build table of contents and offer indexes.

As a writer you don't have to deal a lot with Sphinx if you don't want to. There are a couple of exceptions to this rule:

* If you want to make use of the features Sphinx offers. Check the documentation about `Sphinx markup constructs <http://sphinx-doc.org/markup/index.html>`_.
* If you use a local editor and want to preview how Sphinx will process your reStructuredText file. We will add relevant documentation about using Sphinx locally later. In the mean time you can check the general `Sphinx documentation <http://sphinx-doc.org/contents.html>`_.
* If you're an operator and responsible for the builds of the documentation.

Github
------

In contrast to Sphinx, as a writer you'll have to work with `Github <https://github.com>`_. If you're not familiar with Github `the description Wikipedia offers <http://en.wikipedia.org/wiki/GitHub>`_ might give some insight:

    "GitHub is a Git repository web-based hosting service which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding many of its own features. Unlike Git, which is strictly a command-line tool, GitHub provides a web-based graphical interface and desktop as well as mobile integration."

To break this down, Github is based on software called `Git <http://git-scm.com>`_, which allows groups of developers and writers to collaborate on (software) projects. It is particularly useful for working with plaintext files. `Read more about Git and its extensive featureset <http://git-scm.com/about>`_.

Among other related tools, Github offers a web interface on top of Git. With the web interface you can not only browse the source code of projects, and contributions (called 'commits'), but also edit plaintext files online. As a writer the simplest way to contribute is to use this feature and edit files through the web interface. From the Github interface you'll be able to preview changes to files as well.

If you want to use another text editor or want to work offline you'll have to use Git or the tools provided by Github. `Check the excellent Github documentation <https://help.github.com/>`_.
