---
hackname: You can't touch this (oh-oh oh oh oh-oh-oh)
quicksummary: E-Field gesture recognition used to control TV without touching anything
resource: true
categories: [hack]
---

You can't touch this
====================

The plan is to bring Zattoo's bigscreen/leanback app and recent e-field gesture sensing technology together.
Extra challenge: use open, affordable and portable hardware to run it

Why Do It?
----------

E-Field sensing is not very well explored and is quite portable and affordable compared to other gesture tracking technologies. 
Combined with a real application (Zattoo's leanback/bigscreen app) this could result in a quite promising application targeting two complete different areas:
- People with motor skill disabilities (e.g. Locked-in Syndrome)
- rugged & interactive [Smart/Digital Signage](https://de.wikipedia.org/wiki/Digital_Signage) without exposing any conductive, capacitive or mechanical controls

Requirements
------------

- [x] Zattoo's leanback/bigscreen application (React)
- [x] Raspberry PI's to run it
- [x] Arduino Bluetooth LE controller
- [x] E-field sensors
- [x] More gear for mixing all this ingredients together
- [ ] Feasible plan to pull this off for real 

Could use help with...
----------------------

More experience around Arduino, BluetoothHID and E-Field sensing could be helpful. We kind of have a good plan & setup to glue basic gestures together with Zattoo's leanback expierience. However we are also open to start a sidetrack exploring more complex gestures and evaluate overall quality (resolution, responsiveness) of the [Skywriter](https://shop.pimoroni.de/products/skywriter) sensor.

Links
-----

- https://www.adafruit.com/product/3406 (Arduino Bluetooth Low Energy board)
- https://shop.pimoroni.de/products/skywriter (3D Gesture Sensing Breakout)
- https://shop.pimoroni.de/products/skywriter-hat (same as HAT for raspberry PI)
- http://ww1.microchip.com/downloads/en/DeviceDoc/40001667E.pdf (MGC3130 the E-field controller)

Who's Participating?
--------------------
[Ivo Stock](https://harryf.github.io/tamedia-hackdays/whoami/ivostock.html)
[Bastien Sachs](https://harryf.github.io/tamedia-hackdays/whoami/bastiensachs.html)
[Pavel Verkhovskyi](https://harryf.github.io/tamedia-hackdays/whoami/pavelverkhovskyi.html)
[Bogdan Plieshka](https://harryf.github.io/tamedia-hackdays/whoami/bogdanplieshka.html)
