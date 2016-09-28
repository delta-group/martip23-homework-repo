================
Homework 2
================
----------------
Patrick Martinez - 9/26/2016
----------------

Section 1 - Basic Measurement Units
================

*1 meter = 36inches
    -(12in * 3ft)
*1 mile = 5280feet
    -(google.com)
*1 mile = 1760meters
    -(5280ft / 3ft)
*Circumference of the Earth = 24901miles
    -(google.com)

Section 2 - Basic Terminology
================

*yotta something = 1000\ :sup:`8`\
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*kilo something = 1000 times something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*hecto something = 100 times something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*deca something = 10 times something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*something = something
    -(lol)
*milli something = 1/1000 of something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*micro something = 1/1000000 of something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*nano something = 1/1000000000 of something
    -(https://en.wikipedia.org/wiki/Unit_prefix)
*pico something = 1/1000000000000 of something
    -(https://en.wikipedia.org/wiki/Unit_prefix)

Section 3 - From Physics
==================
*What is the speed of light?*

*186282 miles per second
    -(google.com)
*299792 kilometers per second
    -(google.com)

Section 4 - Speed of Electronic Signals
===================
*How far can an alectronic signal move through a wire:*

*In one nanosecond = 11.80 inches
    -(63360in / 1 mi * 186282mi / sec * 1sec / 1000000000 ns)

*In one microsecond = 327.86 feet
    -(186282mi / 1 sec * 1760ft / 1 mi * 1s / 1000000μs)

*In one millisecond = 186.282 miles
    -(186282mi / 1 sec * 1 sec / 1000 ms)

Section 5 - From our World of Processors
=======================
*Data for Haswell GT2 4C chip*

*Manufacturing Process = 22nm
*Transistor Count = 1.4B
*Die Size = 177mm\ :sup:`2`
    -(http://www.anandtech.com/show/7003/the-haswell-review-intel-core-i74770k-i54560k-tested/5)

*Time for a signal to move between transistors = 0.001 ps
    -sqrt(1.4B) = 37416.57 Transistors on one edge
    -sqrt(264mm) = 16.24mm on each edge
    -(16.24mm / 37416.57T * 1x10\ :sup:`6`\ nm / 1mm = 434nm between transistors
    -(299739km / 1sec * 1000m / 1km * 1*10\ :sup:`9`\ nm / 1m * 1s / 1*10\ :sup:`12`\ ps = 299792nm per picosecond
    =434nm / 299792nm = .001 ps to move between transistors

Section 6 - Counting Up
=====================
*Time to roll over a 64 bit counter = 292.47 yrs (woah)

    -64bit has max value of 9,223,372,036,854,775,807 (Impressed whistle)
    -2.7GHZ = 1,000,000,000 cycles per second
    -(9,223,372,036,854,775,807 / 1000000000sec = 9223372037seconds)
    -(9223372037 sec / 60 / 60 / 24 / 365) = 292.47 yrs
