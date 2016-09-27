*****************************
Restructured Text Cheat Sheet
*****************************

Welcome to my curated RST cheat sheet.  This is a general, but opinionated, approach to writing in RST.  This document will be a vanilla restructured text cheat sheet.  There are actually many different ways to write RST, but in the end it is the level of consistency that you bring to your RST that will truly help you.


.. contents::
   :depth: 2
   :local:


============================================================
Editor Configurations
============================================================


Recommended Plugins - Sublime
------------------------------

* sublime-rst-completion_
* OmniMarkupPreviewer_

Recommended Plugins - Atom
--------------------------

* language-restructuredtext_
* rst-preview-pandoc_

============================================================
Text
============================================================

Italics
-------

.. code-block:: bash

    *italic text*

*This is example italic text*

Bold
----

.. code-block:: bash

    **bold text**

**This is example bold text**


============================================================
Lists
============================================================

Flat Lists - Bullets
--------------------

.. code-block:: bash

    * bullet point 1
    * bullet point 2

* bullet point 1

  - bullet point 1.1

Flat Lists - Numbered
---------------------

.. code-block:: bash

    1.  First item in list
    2.  Second item in list

1.  First item in list
2.  Second item in list

Nested Lists - bullets
----------------------

.. code-block:: bash

    * bullet point 1

      - bullet point 1.1

    * bullet point 2

      - bullet point 2.1


* bullet point 1

  - bullet point 1.1

* bullet point 2

  - bullet point 2.1

============================================================
Images
============================================================


============================================================
Links
============================================================

External Links - Single
-----------------------

.. code-block:: bash

    Google_

    .. _Google: http://www.google.ca

Google_

.. _Google: http://www.google.ca

.. epigraph::

   Use for a single word


External Links - Phrase
-----------------------

.. code-block:: bash

    `Google is a search engine`_

    .. _Google: http://www.google.ca

`Google is a search engine`_

.. _Google is a search engine: http://www.google.ca

.. epigraph::

   Use for a phrase

External Links - Sentences
--------------------------

.. code-block:: bash

    JavaScript_ is `awesome`__.

    .. _JavaScript: https://github.com/sorrycc/awesome-javascript

    __ JavaScript_


JavaScript_ is `awesome`__.

.. _JavaScript: https://github.com/sorrycc/awesome-javascript

__ JavaScript_

.. epigraph::

   Use when you want to highlight multiple words or phrases in a sentence / paragrah


============================================================
Headers and Quotes
============================================================

Section - Title
---------------

.. code-block:: bash

    **************
    READEME TITLE
    **************

.. epigraph::

   I prefer to only use one of these per RST file


Section - Chapter
-----------------

.. code-block:: bash

    ================
    README CHAPTER
    ================

.. epigraph::

   Use as many as you like.


Section - Section
-----------------

.. code-block:: bash

    READEME SECTION
    ---------------

.. epigraph::

   Use as many as you like.


Section - Sub Section
---------------------

.. code-block:: bash

    READEME SUB SECTION
    ~~~~~~~~~~~~~~~~~~~

.. epigraph::

   Use as many as you like.


Section - Sub Sub Section
-------------------------

.. code-block:: bash

    READEME SUB SUB SECTION
    .......................

.. epigraph::

   Use as many as you like.

============================================================
Code
============================================================

Inline
------

.. code-block:: bash

    ``RST`` is a great ``markup`` language

``RST`` is a great ``markup`` language


Blocks
------

.. code-block:: bash

    .. code-block:: javascript

        // this will inherit JS syntax highlighting

.. code-block:: javascript

    const MARKUP = true;

.. epigraph::

   By replacing ``javascript`` for the language of your choice, the syntax highlighting will change accordingly


============================================================
Extras
============================================================

Table of Contents
-----------------

.. code-block:: bash

    .. contents::
       :depth: 2
       :local:

.. epigraph::

   Add this to the top of your RST file.  Note that we use the ``local`` directive.  This tells the table of contents to only include headers below the physical placement of the above code.  See this documents source code as an example


============================================================
Resources
============================================================

.. _sublime-rst-completion: https://github.com/mgaitan/sublime-rst-completion
.. _OmniMarkupPreviewer: https://packagecontrol.io/packages/OmniMarkupPreviewer
.. _language-restructuredtext: https://atom.io/packages/language-restructuredtext
.. _rst-preview-pandoc: https://atom.io/packages/rst-preview-pandoc
.. _Google: http://www.google.ca

============================================================
Special Thanks
============================================================

The structure for this document is borrowed from https://guides.github.com/features/mastering-markdown/


