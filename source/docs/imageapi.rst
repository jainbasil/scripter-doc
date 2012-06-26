.. highlight:: rst

:class:`ImageAPI`
=========================

.. py:class:: ImageAPI

   :class:`ImageAPI` is used to access an Image Item in a Scribus document. It inherits the attributes and methods of :class:`ItemAPI`, along with the following Attributes and Methods.

:class:`ImageAPI` Attributes
-------------------------------

.. py:attribute:: ImageAPI.xScale

   Used to read/write the Image Scale along X Axis.
 
       >>> print imageItem.xScale #reading the xScale
       1.0
       >>> imageItem.xScale = 0.5 #setting the value of xScale
       >>>

.. py:attribute:: ImageAPI.yScale

   Used to read/write the Image Scale along Y Axis.

       >>> print imageItem.yScale #reading the yScale
       1.0
       >>> imageItem.yScale = 2.0 #setting the value of yScale
       >>>

.. py:attribute:: ImageAPI.xOffset

   Used to read/write the Image Offset along X Axis.

       >>> print imageItem.xOffset #reading the xOffset
       0.0
       >>> imageItem.xOffset = 2.0 #setting the value of xOffset
       >>>

.. py:attribute:: ImageAPI.yOffset

   Used to read/write the Image Offset along Y Axis.

       >>> print imageItem.yOffset #reading the yOffset
       0.0
       >>> imageItem.yOffset = 2.0 #setting the value of yOffset
       >>>

:class:`ImageAPI` Methods
--------------------------

.. py:method:: ImageAPI.load(filename)

   Load an image into the Image Frame.
   
   :param filename: name of the image file to be loaded into the image frame.
      
   >>> imageItem.load("/Users/scribus/logo.jpg")
   >>>


.. py:method:: ImageAPI.scale(x, y)

   Set the scaling of loaded image.
   
   :param x: Set the scaling along X Axis.
   :param y: Set the scaling along Y Axis.
  

.. py:method:: ImageAPI.offset(x, y)

   Set the offsets of loaded image.

   :param x: Set the offset along X Axis.
   :param y: Set the offset along Y Axis.

.. py:method:: ImageAPI.setBrightness(amount)

   Set the brightness of the loaded image.

   >>> imageItem.setBrightness(100)
   >>>

.. py:method:: ImageAPI.setGrayscale()

   Set the loaded image to Grayscale.

   >>> imageItem.setGrayscale()
   >>>

.. py:method:: ImageAPI.scaleToFrame(scale, proportional)

   Scale the loaded image to image frame.
   
   :param scale: Set True for scaleToFrame.
   :param proportional: Set True for scaling proportionally.

   >>> imageItem.scaleToFrame(True, True)
   >>>





