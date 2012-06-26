.. highlight:: rst

:class:`TextAPI`
========================

.. py:class:: TextAPI

   :class:`TextAPI` inherits :class:`ItemAPI`. It adds attributes and methods that are specific to Text Items in a Scribus document.

:class:`TextAPI` Attributes
-----------------------------------

.. py:attribute:: TextAPI.font

   Used to get/set the font of text frame.

   >>> textItem.font
   u'Arial Regular'
   >>> textItem.font = "Times New Roman Regular"
   >>>

.. py:attribute:: TextAPI.fontSize

   Used to get/set the font size of text frame.

   >>> textItem.fontSize
   12.0
   >>> textItem.fontSize = 18.0
   >>> 

.. py:attribute:: TextAPI.text

   Used to get/set the text in text frame.

   >>> textItem.text
   u'This is a sample text'
   >>> textItem.text = "Sample text has been changed"
   >>> 

   Note that using this function to set text content will erase the existing content in text frame.
   
.. py:attribute:: TextAPI.textLines

   Used to get the number of lines in the content of text frame.

   >>> textItem.textLines
   1
   >>> 

.. py:attribute:: TextAPI.textLength

   Used to get the length of text content in the frame.

   >>> textItem.textLength
   28
   >>> 

.. py:attribute:: TextAPI.lineSpacing

   Used to get/set the linespacing for text frame.

   >>> textItem.lineSpacing
   15.0
   >>> textItem. lineSpacing = 16.0
   >>> 

.. py:attribute:: TextAPI.distances

   Used to get the text distances of the frame. It will return a list.

   >>> textItem.distances
   [0.0, 0.0, 0.0, 0.0]
   >>>

.. py:attribute:: TextAPI.deleteText

   Used to delete the text in a text frame.
   
   >>> textItem.deleteText
   >>>

.. py:attribute:: TextAPI.traceText

   Used to trace the text frame.

   >>> textItem.traceText
   True
   >>> 

.. py:attribute:: TextAPI.hyphenate

.. py:attribute:: TextAPI.dehyphenate

.. py:attribute:: TextAPI.PDFBookMark

:class:`TextAPI` Methods
-------------------------------------

.. py:method:: TextAPI.insertText(text, position)

.. py:method:: TextAPI.setLineSpacing(mode)

.. py:method:: TextAPI.setDistances(left, right, top, bottom)

.. py:method:: TextAPI.setTextColor(color)

.. py:method:: TextAPI.setTextStroke(color)

.. py:method:: TextAPI.setTextScalingV(value)

.. py:method:: TextAPI.setTextScalingH(value)

.. py:method:: TextAPI.setTextShade(shade)

.. py:method:: TextAPI.selectText(start, selectCount)

.. py:method:: TextAPI.linkToTextFrame(name)

.. py:method:: TextAPI.unLinkTextFrames()
