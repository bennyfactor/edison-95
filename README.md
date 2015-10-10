HP 95LX Block for Intel Edison - Battery/Serial
=================================================


Based on the [SparkFun Block for Intel Edison - Battery/Power (DEV-13037)](https://www.sparkfun.com/products/13037)
and the reference design for the [MAX3218 low voltage TTL-RS232 transciever](https://datasheets.maximintegrated.com/en/ds/MAX3218.pdf)


This block or daughterboard, or whatever, is designed to fit in to the physical dimensions of the HP 95LX palmtop computer's
proto-PCMCIA slot. It has connections for two UARTs (the Edison's console out, and COM1?) that will allow either one to be connected to the HP95LX's serial header.
It also has the battery circuit for a lithium battery based on Sparkfun's design so that it can run on its own power while inside the palmtop!

Simply plug in a micro USB cable to charge.
The power switch removes the battery from the Edison while allowing it to charge via the microUSB cable.

Also fun LEDs for power status!

Repository Contents
-------------------
* **/hardware** - Eagle design files (.brd, .sch)

Documentation
--------------
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-blocks-for-intel-edison---battery-block)** - Basic hookup guide for the SparkFun battery/power block.
* **[MAX3218 low voltage TTL-RS232 transciever](https://datasheets.maximintegrated.com/en/ds/MAX3218.pdf)** - Datasheet for the serial tranceiver.
* **[Intel Edison Hardware Guide](http://download.intel.com/support/edison/sb/edisonmodule_hg_331189004.pdf)** - Datasheet for the Edison module.

Sparkfun Product Versions
----------------
* [Battery Block](https://www.sparkfun.com/products/13037)- Battery block.
* [Power Block](https://www.sparkfun.com/products/13727)- Battery block without lipo battery installed.

License Information
-------------------

This product is _**open source**_!

Please review the LICENSE.md file for license information.

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Distributed as-is; no warranty is given.

- Your friends at SparkFun. ALSO BENNY