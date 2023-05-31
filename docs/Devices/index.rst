.. _Devices:

Devices
=========================================

we can also copy source code verbatim (i.e. include it in the rst
document) like this::

   TYPE E_TurnTablePos :
   (
	  Unknown := 0, 		//The position is unkwown, should only happen after startup
	  Vacuum := 1,			//The turntable is at the vacuum position
	  Saw := 2, 			//The turntable is at the Saw position
	  Belt := 3			//The turntable is at the Belt position. 
   );

An image of a machine!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. figure:: /_Images/Factory.png


   Png is a file format that is both acceptable for html pages as well as for (pdf)latex.

---------------------------------------------------------------------------

.. Warning::
   A warning can also be added, to let the reader know to pay attention!!


.. toctree::
   :maxdepth: 1
   :hidden:

   BL20_PG_EN_V3//index
