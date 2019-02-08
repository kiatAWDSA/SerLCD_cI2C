# SerLCD_cI2C
===========================================================
This is a derivative of the Sparkfun library for controlling an LCD screen. The original library uses the in-built Wire library in Arduino distributions for I2C communication. Unfortunately, the Wire library has been known to block indefinitely in rare circumstances, which is undesirable for equipment that will be operating for a long time. This library utilizes a custom non-blocking I2C library to solve that problem.

Sparkfun SerLCD library: https://github.com/sparkfun/SparkFun_SerLCD_Arduino_Library

Custom I2C library: https://github.com/kiatAWDSA/I2C

Blocking behavior of Wire libary (search for "blocking"):
 - https://playground.arduino.cc/Main/WireLibraryDetailedReference
 - https://arduino.stackexchange.com/a/30354

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.
