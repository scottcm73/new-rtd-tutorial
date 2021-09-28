Rotate Model
============

Rotate Model Around X-axis
--------------------------

Click your mouse on any point on the model or the display window and hold down the button. Then move the mouse straight up (towards the screen) while holding the mouse button down.
If you moved the mouse straight up, the Z-axis and Y-axis shifted and the model rotated around the X-axis. The blue Z-axis should cover part of the green Y-axis. 

.. image:: images/Python-Open3D-Examples-Gui-mouse-up-rotate-around-x-axis.png
  :width: 400
  :alt: Alternative text

Then, if you keep moving the mouse straight up, the model will continue rotating around the X-axis until the Z-axis completely covers the Y-axis. 

.. image:: images/Python-Open3D-Examples-Gui-mouse-up2-rotate-around-x-axis.png
  :width: 400
  :alt: Alternative text

Now, move the mouse straight down while pressing the mouse button on the display window until the Z-axis is just a point in the front. Try to get it as close to the original orientation as you can.


Rotate Model Around Y-axis
--------------------------

Again, press and hold the mouse button down at any point on the model or the display window. This time attempt to move the mouse precisely left. You will see that moving the mouse left rotates the model around the Y-axis.

.. image:: images/Python-Open3D-Examples-Gui-mouse-left-rotate-around-y-axis.png
  :width: 400
  :alt: Alternative text


Now slide the mouse right. You will see the blue Z-axis completely covers the red X-axis with only a slight bump visible for the X-axis arrow.
 
.. image:: images/Python-Open3D-Examples-Gui-mouse-right-rotate-around-y-axis.png
  :width: 400
  :alt: Alternative text

Try moving the mouse diagonally up and to the right. Diagonal mouse movement makes the model rotate around the X and Y axes relative to the model's initial orientation. 
 
.. image:: images/Python-Open3D-Examples-Gui-mouse-diagonal-rotation.png
  :width: 400
  :alt: Alternative text

Slide the mouse up and to the left now. You will notice that the model doesn't rotate around any particular axis. It turns around the points in the model that are directly facing up (originally the Y- axis), directly right (originally the X-axis), and directly forward (originally the Z-axis) relative to the current position. 
 
.. image:: images/Python-Open3D-Examples-Gui-mouse-diagonal-up-left-rotation.png
  :width: 400
  :alt: Alternative text 

The position of your model will likely vary from this significantly depending upon the diagonal mouse direction you chose.
