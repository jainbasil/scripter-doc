.. highlight:: rst

:class:`DocumentAPI`
====================

.. py:class:: DocumentAPI

   :class:`DocumentAPI` provides properties and methods needed to interact with a Scribus document. An instance of DocumentAPI may be obtained from :class:`Scripter`, for eg. ::

    document = Scripter.activeDocument

:class:`DocumentAPI` Attributes
-------------------------------

.. py:attribute:: DocumentAPI.name

   Read the name of current document.::
   
       print document.name
       
   This will be empty for a new document.

   
.. py:attribute:: DocumentAPI.available

	Returns True if the document is available, else False.::
	
	    >>> document = Scripter.activeDocument
	    >>> print document.available
	    True
	    >>> 
	

:class:`DocumentAPI` Methods
----------------------------

.. py:method:: DocumentAPI.close()

   Close a document.