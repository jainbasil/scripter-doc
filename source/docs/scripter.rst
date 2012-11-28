.. highlight:: rst

:class:`Scripter`
=================

.. py:class:: Scripter

   The entry point to Scripting Engine of Scribus. It provides necessary methods to create new document, open an existing document etc., as documented in this section.

:class:`Scripter` Attributes
----------------------------

.. py:attribute:: Scripter.activeDocument

   Instance of active document.
   
.. py:attribute:: Scripter.activeWindow

   Instance of active scribus window.

.. py:attribute:: Scripter.colors

.. py:attribute:: Scripter.language

.. py:attribute:: Scripter.fontInfo

.. py:attribute:: Scripter.extendedFontInfo

:class:`Scripter` Methods
-------------------------
.. py:method:: Scripter.openDocument(docName)

   Open an existing scribus document.
   
.. py:classmethod:: Scripter.newDocument(topMargin, bottomMargin, leftMargin, rightMargin, pageWidth, pageHeight, orientation, firstPageNumber, unit, pagesType, facingPages, firstPageOrder, numberOfPages)
   
   Create a new document.

   :param topMargin: Top Margin for the new document
   :type topMargin: double
   :param bottomMargin: Bottom Margin for the new document
   :type bottomMargin: double
   :param leftMargin: Left margin for the new document
   :type leftMargin: double
   :param rightMargin: Right margin for the new document.
   :type rightMargin: double
   :param pageWidth: Width of the page.
   :type pageWidth: double
   :param pageHeight: Height of the page.
   :type pageHeight: double
   :param orientation: Orientation for the page.
   :type orientation: Integer
   :param firstPageNumber: First page number
   :type firstPageNumber: Integer
   :param unit: Unit
   :type unit: Integer
   :param pagesType: Type of pages
   :param pagesType: Integer
   :param facingPages: facing pages.
   :type facingPages: Integer
   :param firstPageOrder: first page order
   :type firstPageOrder: Integer
   :param numPages: number of pages
   :type numPages: Integer
   :rtype: :class:`DocumentAPI` instance