.. highlight:: rst

:class:`TextAPI`
========================

.. py:class:: TextAPI

   :class:`TextAPI` inherits :class:`ScribusItem`. It adds attributes and methods that are specific to Text Items in a Scribus document.

:class:`TextAPI` Attributes
-----------------------------------

.. py:attribute:: TextAPI.font

.. py:attribute:: TextAPI.fontSize

.. py:attribute:: TextAPI.text

.. py:attribute:: TextAPI.textLines

.. py:attribute:: TextAPI.textLength

.. py:attribute:: TextAPI.allText

.. py:attribute:: TextAPI.lineSpacing

.. py:attribute:: TextAPI.distances

.. py:attribute:: TextAPI.deleteText

.. py:attribute:: TextAPI.traceText

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
