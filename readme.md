# DS3231
Arduino Library for the DS3231 Real-Time Clock chip

Updated version of the library originally provided by [Eric Ayars](http://hacks.ayars.org/2011/04/ds3231-real-time-clock.html)

Main changes:

- Updated for Arduino >= 1.5
- Added a method that resets all control & status registers and (re-)enables the alarm interrupt. Some control bits like to randomly toggle when the power is transfered from the backup battery to `Vcc`. (I am looking at you, `INTCN`)


This software is released into the public domain, see LICENSE for details.


Original copyright header:

```
/*
 * Arduino Library for the DS3231 Real-Time Clock chip
 *
 * (c) Eric Ayars
 * 4/1/11
 * released into the public domain. If you use this, please let me know
 * (just out of pure curiosity!) by sending me an email:
 * eric@ayars.org
 */
```
