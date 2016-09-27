*****************************
Restructured Text Cheat Sheet
*****************************

Welcome to my curated RST cheat sheet.  I hope to provide a one-stop-shop for RST knowledge with the focus being on practical application.  This document will be a vanilla restructured text cheat sheet.  This means that what I am documenting should work everywhere.


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

Flat Lists
----------

.. code-block:: bash

    # ----------------------------
    # flat list
    # ----------------------------

    * bullet point 1
    * bullet point 2

* bullet point 1

  - bullet point 1.1



Nested Lists
------------

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
Headers and Quotes
============================================================


============================================================
Code
============================================================


============================================================
Extras
============================================================

============================================================
Resources
============================================================

.. _sublime-rst-completion: https://github.com/mgaitan/sublime-rst-completion
.. _OmniMarkupPreviewer: https://packagecontrol.io/packages/OmniMarkupPreviewer
.. _language-restructuredtext: https://atom.io/packages/language-restructuredtext
.. _rst-preview-pandoc: https://atom.io/packages/rst-preview-pandoc

============================================================
Special Thanks
============================================================

The structure for this document is borrowed from https://guides.github.com/features/mastering-markdown/


