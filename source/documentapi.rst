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
	    >>> document.available
	    True
	    >>> 
	

:class:`DocumentAPI` Methods
----------------------------

.. py:method:: DocumentAPI.close()

   Closes a document. Returns True is successful, else return False.
   
       >>> document = Scripter.activeDocument
       >>> document.close()
       True
       >>>
       
.. py:method:: DocumentAPI.save()

   Saves the current document, and return True is successful. If the document is a new one (i.e., you are trying to save it for the first time), calling this function will result in invocation of Save As dialog, where you can enter the name for your document.
   
       >>> document = Scripter.activeDocument
       >>> document.save()
       True
       >>>
