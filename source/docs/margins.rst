.. highlight:: rst

:class:`Margins`
================

.. py:class:: Margins

   :class:`Margins` represents the margins of a document.
   
:class:`Margins` Attributes
---------------------------

.. py:attribute:: Margins.top

   This attribute is used to read/write the top margin of the document.::
   
       >>> document = Scripter.activeDocument
       >>> margins = document.margins
       >>> margins.top
       40.0
       >>> margins.top = 60
       >>> margins.top
       60.0
       >>>
 

.. py:attribute:: Margins.bottom

   This attribute is used to read/write the bottom margin of the document.::
   
       >>> document = Scripter.activeDocument
       >>> margins = document.margins
       >>> margins.bottom
       40.0
       >>> margins.bottom = 60
       >>> margins.bottom
       60.0
       >>>
   
   
.. py:attribute:: Margins.right

   This attribute is used to read/write the right margin of the document.
   
       >>> document = Scripter.activeDocument
       >>> margins = document.margins
       >>> margins.right
       40.0
       >>> margins.right = 60
       >>> margins.right
       60.0
       >>>
   
.. py:attribute:: Margins.left

   This attribute is used to read/write the left margin of the document.
   
       >>> document = Scripter.activeDocument
       >>> margins = document.margins
       >>> margins.left
       40.0
       >>> margins.left = 60
       >>> margins.left
       60.0
       >>>
   
:class:`Margins` Methods
------------------------

.. py:method:: Margins.set(left, top, bottom, right)
   
   :meth:`set` is used to set the margins of a document. All the parameters are of type float. 
