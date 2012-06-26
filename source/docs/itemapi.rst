.. highlight:: rst

:class:`ItemAPI`
====================

.. py:class:: ItemAPI
   
   :class:`ItemAPI` represents an item in Scribus document. :class:`TextAPI` and :class:`ScribusImageItem` are inherited from this class to provide more specific attributes and methods to it. All the attributes and methods of :class:`ItemAPI` are applicable to :class:`TextAPI` and :class:`ImageAPI`.

:class:`ItemAPI` Attributes
-------------------------------

.. py:attribute:: ItemAPI.itemName
.. py:attribute:: ItemAPI.fillColor
.. py:attribute:: ItemAPI.lineColor
.. py:attribute:: ItemAPI.fillShade
.. py:attribute:: ItemAPI.lineShade
.. py:attribute:: ItemAPI.fillTransparency
.. py:attribute:: ItemAPI.lineTransparency
.. py:attribute:: ItemAPI.locked
.. py:attribute:: ItemAPI.sizeLocked
.. py:attribute:: ItemAPI.flipVertical
.. py:attribute:: ItemAPI.flipHorizontal
.. py:attribute:: ItemAPI.lineWidth
.. py:attribute:: ItemAPI.customLineStyle
.. py:attribute:: ItemAPI.startArrowIndex
.. py:attribute:: ItemAPI.endArrowIndex
.. py:attribute:: ItemAPI.printEnabled
.. py:attribute:: ItemAPI.xPos
.. py:attribute:: ItemAPI.yPos
.. py:attribute:: ItemAPI.width
.. py:attribute:: ItemAPI.height
.. py:attribute:: ItemAPI.rotation
.. py:attribute:: ItemAPI.reversed
.. py:attribute:: ItemAPI.cornerRadius
.. py:attribute:: ItemAPI.columnGap
.. py:attribute:: ItemAPI.columns

:class:`ItemAPI` Methods
-----------------------------

.. py:method:: ItemAPI.move(dx, dy)
.. py:method:: ItemAPI.moveAbs(x, y)
.. py:method:: ItemAPI.rotate(rotation)
.. py:method:: ItemAPI.rotateAbs(rotation)
.. py:method:: ItemAPI.resize(width, height)
