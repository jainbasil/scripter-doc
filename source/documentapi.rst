.. highlight:: rst

:class:`DocumentAPI`
====================

.. py:class:: Document

   :class:`DocumentAPI` provides properties and methods needed to interact with a Scribus document. An instance of DocumentAPI may be obtained from :class:`Scripter`, for eg. ::

    document = Scripter.activeDocument

:class:`DocumentAPI` Attributes
-------------------------------

.. py:attribute:: DocumentAPI.name

   Read the name of current document.::
   
       println document.name
       
   This will be empty for a new document.
       

:class:`DocumentAPI` Methods
----------------------------
