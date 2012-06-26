.. highlight:: rst

:class:`ScribusItem`
====================

.. py:class:: ScribusItem
   
   :class:`ScribusItem` represents an item in Scribus document. :class:`ScribusTextItem` and :class:`ScribusImageItem` are inherited from this class to provide more specific attributes and methods to it. All the attributes and methods of :class:`ScribusItem` are applicable to :class:`ScribusTextItem` and :class:`ScribusImageItem`.

:class:`ScribusItem` Attributes
-------------------------------

.. py:attribute:: ScribusItem.itemName
.. py:attribute:: ScribusItem.fillColor
.. py:attribute:: ScribusItem.lineColor
.. py:attribute:: ScribusItem.fillShade
.. py:attribute:: ScribusItem.lineShade
.. py:attribute:: ScribusItem.fillTransparency
.. py:attribute:: ScribusItem.lineTransparency
.. py:attribute:: ScribusItem.locked
.. py:attribute:: ScribusItem.sizeLocked
.. py:attribute:: ScribusItem.flipVertical
.. py:attribute:: ScribusItem.flipHorizontal
.. py:attribute:: ScribusItem.lineWidth
.. py:attribute:: ScribusItem.customLineStyle
.. py:attribute:: ScribusItem.startArrowIndex
.. py:attribute:: ScribusItem.endArrowIndex
.. py:attribute:: ScribusItem.printEnabled
.. py:attribute:: ScribusItem.xPos
.. py:attribute:: ScribusItem.yPos
.. py:attribute:: ScribusItem.width
.. py:attribute:: ScribusItem.height
.. py:attribute:: ScribusItem.rotation
.. py:attribute:: ScribusItem.reversed
.. py:attribute:: ScribusItem.cornerRadius
.. py:attribute:: ScribusItem.columnGap
.. py:attribute:: ScribusItem.columns

:class:`ScribusItem` Methods
-----------------------------

.. py:method:: ScribusItem.move(dx, dy)
.. py:method:: ScribusItem.moveAbs(x, y)
.. py:method:: ScribusItem.rotate(rotation)
.. py:method:: ScribusItem.rotateAbs(rotation)
.. py:method:: ScribusItem.resize(width, height)
