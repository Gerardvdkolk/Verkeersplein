.. _Pous:

POU's
========
The homePage of the ``POUs`` files

.. image:: /_Images/POUsPage.png


How are the folders structured?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
The short answer: Exactly the same as the folder structure in ``CODESYS``.

However the static folder ``_Images`` *(which contains all the images used in these pages)* is not added. 
Also .TXT files namend ``ProjectInfo`` or ``FolderInfo`` are not added in the structure. 

The ``ProjectInfo`` file is parsed into the homepage. 
A ``FolderInfo`` file is parsed into the page off the folder. The text you're reading right now is also present in a ``ProjectInfo`` file.

How do i exactly create a custom page for a folder?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Create the folder in CODESYS
2. Create a FolderInfo txt file inside this folder (the script automaticaly parses the text into the folder ``html`` page.)

.. image:: /_Images/CreateHomepage.png


.. toctree::
   :maxdepth: 1
   :hidden:

   FolderOne//index
   Structure.rst
