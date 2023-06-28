============
RST Test Page
============

This page tests MD support in base read the docs and shall go over some features that should work in a basic page

Lists
-----

Lists like these should work

* Item 1
* Item 2

    * Subitem 1
    * Subitem 2
    * Subitem 3

* Item 3
  
Item 3 in particular is of note so it should be **bold**
Italics should also ``function`` in this text. We *shall* try now

Code example 

.. code-block::
    :caption: Heres some code 
    
    code.sh
    test loop () {
        for i in x; do
        echo "hi"
    done
    }

Example links:

This paragraph contains several hyperlinks. heres `a link`_. Heres `another link`_.

.. _a link: https://ncar.ucar.edu/what-we-offer/computational-resources
.. _another link: https://en.wikipedia.org/wiki/NCAR-Wyoming_Supercomputing_Center

Images
------

.. image::
    :target: https://kb.ucar.edu/download/attachments/embedded-page/RC/User%20documentation%20for%20NCAR%20high-performance%20computing/derecho_logo1600X560.png?api=v2
+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

