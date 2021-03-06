.. include:: ../../Includes.txt
.. highlight:: rst


===================
Problems with Lists
===================

If you use lists, make sure there is an empty line before and after the
list. If you use lists with sublevels, make sure there is an empty line
between the levels.

The same applies for bullet lists and enumerated lists.


Correct Syntax
==============

Example 1: Bullet List
~~~~~~~~~~~~~~~~~~~~~~

::

   this is some text

   * this is a list item
   * another item

   more text

**How it looks:**

   this is some text

   * this is a list item
   * another item

   more text


Example 2: List with Sublist
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

   this is some text

   * this is a list item

      * this is a sublevel list item
      * another item

   this is more text


How it looks:

   this is some text

   * this is a list item

      * this is a sublevel list item
      * another item

   this is more text


Wrong Syntax
------------

::

   this is some text
   * this is a list item
   * another item
   more text

How it looks:

   this is some text
   * this is a list item
   * another item
   more text


Additional Information
======================

* `Docutils cheat-sheet for reStructuredText: Bullet list
  <http://docutils.sourceforge.net/docs/user/rst/quickref.html#bullet-lists>`__
* :ref:`Section on lists in this guide <rest-lists>`
* `Docutils cheat-sheet for reStructuredText: Enumerated lists
  <http://docutils.sourceforge.net/docs/user/rst/quickref.html#enumerated-lists>`__
