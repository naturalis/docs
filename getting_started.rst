Getting started
===============

To get going you need to arrange a couple of things. Below, all necessary steps are explained in detail.


Make a Github account
---------------------

If you don't have a Github account, please `sign up for one <https://github.com/join>`_. Choose the free plan.

After you've made the account, make an `ICT Support call <http://ictsupport.naturalis.nl>`_ with the request to join the Naturalis organization on Github.

All documentation projects at Naturalis are managed in separate '`repositories <http://en.wikipedia.org/wiki/Repository_%28version_control%29>`_' (the set of version controlled files and directories). The names of these repositories is structured as '<projectname>-docs'. You can look up and search the existing repositories on `github.com/naturalis <https://github.com/naturalis>`_. Please mention the repository you want to work at in the support call.


Choose your workflow
--------------------

As explained in the introduction there are basically two workflow options:

* Use the Github webinterface to edit files
* Use a Git client to synchronize files in the Github repository with a folder on your computer and use a local editor of choice

Both methods are explained below.

Github webinterface
^^^^^^^^^^^^^^^^^^^

Using the webinterface is pretty simple and might be the best option if you're not acquainted with the use of Git and just want to get started quickly:

#. First of all, `login <https://github.com/login>`_ to your Github account.
#. Go to the `Naturalis page on Github <https://github.com/naturalis>`_ and search for the repository you want to work in.

To edit an existing file follow these steps:

#. In the list of files, click on the one you want edit. For each section there will be a file with an rst-extension.
#. Click on the pencil icon on the top right to start editing. 
#. To check how the code will be rendered on Github click on the Preview tab.
#. When you're finished editing add a short description of the changes you've made under 'Commit changes' and click the button with the same name.

To add a new section follow these steps

#. In the top directory of the repository (e.g. `github.com/naturalis/nba-docs <https://github.com/naturalis/nba-docs>`_) click on the '+' icon to add a file
#. Add a name with 'rst' as extension and underscores in place of spaces (e.g. getting_started.rst)
#. Edit and commit the file as explained above.

Git client
^^^^^^^^^^

As explained, the other way to contribute is to use a Git client to synchronize changes to the repository between your computer and Github. 

On Linux you might be using git from the command line, on Windows you might want to take a look at `Github for Windows <https://windows.github.com/>`_.

Please check out the `Github documentation <https://help.github.com/>`_ about the `Git workflow <https://help.github.com/categories/19/articles>`_, the `setup of the different clients <https://help.github.com/articles/set-up-git>`_ and the specifics of Github.

Depending on your editor or IDE of choice the reStructuredText syntax might be highlighted. Some editors offer more support. Eclipse, for example, `has a plugin available <http://resteditor.sourceforge.net/>`_ that offers some nice extras.

Working with reStructuredText
-----------------------------

As with everything, working with reStructuredText might need some getting used to. Probably the best advice is to just practice a bit. 

To get started, it is recommended to first go through the `reStructuredText primer the Sphinx people wrote <http://sphinx-doc.org/rest.html>`_. Most of the markup you'll need is covered in this document. 

.. tip::
   An important thing to remember, mentioned at the start of the primer, is that "indentation is significant in reST", meaning that "all lines of the same paragraph must be left-aligned to the same level of indentation."

Another useful document is the `quick reference provided by the developers of reStructuredText <http://docutils.sourceforge.net/docs/user/rst/quickref.html>`_.

Last but not least, you can always have a look at `this documentation <https://github.com/naturalis/docs>`_ for example code and structuring of the repository.