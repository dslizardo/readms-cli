********
Overview
********
A cli tool for downloading latest manga on https://readms.net


Requirements
============
* python3.x
* pip


Installation
============
.. code-block:: bash

 $ pip install readms-cli

*Note: You might need to manually add readms on your system PATH*

Usage
============

* List latest manga on readms

  .. code-block:: bash

   $ readms latest
* Download manga, Note: Run "readms latest" first to see available manga for download

  .. code-block:: bash

   #Template $ readms download "${name}"
   #Examples
   $ readms download "Boruto"
   $ readms download "One Piece"
