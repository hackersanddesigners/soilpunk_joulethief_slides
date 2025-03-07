:title: Soilpunk Joulethief
:author: Heerko van der Kooij
:description: 
:css: slides.css

.. header::

  Soilpunk 🌏🤘 - Joulethief

----

Soilpunk - Joulethief
======================

This document is viewable as `a webpage <https://github.com/hackersanddesigners/soilpunk_joulethief_slides/blob/master/slides.rst>`_ or as `a slideshow <https://hackersanddesigners.github.io/soilpunk_joulethief_slides/html_output/index.html>`_

----

:id: joulethief

Joulethief
========================

.. image:: ./assets/images/joulethief_simple.jpeg

----

Transistor
==========

.. image:: ./assets/images/transistor.png
	:width: 300
.. image:: ./assets/images/analogi-transistor-87050130.gif
	:width: 500

Water analogy: the little bit of water from B to E opens the gate for the bigger flow from C to E

----

Joulethief
========================

.. image:: ./assets/images/joulethief.jpeg

----

:id: joulethief-step1

Joulethief
========================

.. image:: ./assets/images/joulethief_1.png
 
A small current flows from the battery through the coil and the base-emitter path of the transistor. This opens the emittor-collector path of the transistor.

----

Joulethief
========================

.. image:: ./assets/images/joulethief_2.png
	
Electricity is now able to travel through the second coil and through the collector-emitter channel of the transistor.

----

Joulethief
========================

.. image:: ./assets/images/joulethief_3.png
	
The increasing amount of electricity through the second coil generates a negative voltage in the first coil, which cause the transistor to close. 

----

Joulethief
========================

.. image:: ./assets/images/joulethief_4.png

With the transistor closed the energy starts to flow through the output (led).

----

Joulethief
========================

.. image:: ./assets/images/joulethief_5.png

The inductor is now powered by the magnetic field of the coil. 

----

Joulethief
========================

.. image:: ./assets/images/joulethief_6.png

When the magnetic field is gone, the whole process `starts over <#joulethief-step1>`_.

----

Joulethief
========================
A more detailed explanation can be found on `instructables <https://www.instructables.com/Joule-Thief-Circuit-How-to-Make-and-Circuit-Explan/>`_

----

Led
========================

.. image:: ./assets/images/led_polarity.png

Make sure to get the LED polarity right. Short leg goes to ground!

----

Circuit
========================

.. image:: ./assets/images/circuit.png

https://github.com/hackersanddesigners/Soilpunk_joulethief
