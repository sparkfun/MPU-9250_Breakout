9 Degrees of Freedom - MPU-9250 Breakout
========================================

![9 Degrees of Freedom - MPU-9250 Breakout](https://cdn.sparkfun.com/assets/parts/1/1/3/0/6/13762-00a.jpg)

[*9 Degrees of Freedom - MPU-9250 Breakout (SEN-13762)*](https://www.sparkfun.com/products/13762)

The MPU-9250 is an accelerometer, gyro, and magnetometer all in a single package with an I<sup>2</sup>C. [The datasheet can be found here.](https://cdn.sparkfun.com/assets/learn_tutorials/5/5/0/MPU9250REV1.0.pdf)

There are two SparkFun Arduino libraries available for this sensor:

* [SparkFun MPU-9250 Breakout Library](https://github.com/sparkfun/SparkFun_MPU-9250_Breakout_Arduino_Library) -- Simple Arduino library that supports all accelerometer, gyroscope, and magnetometer reads from the MPU-9250.
* [SparkFun MPU-9250 Digital Motion Processing (DMP) Arduino Library](https://github.com/sparkfun/SparkFun_MPU-9250-DMP_Arduino_Library) -- More advanced library that includes support for the MPU-9250's digital motion processing (DMP) library. This provides support for features like tap-detection, orientation-detection, step-counting (pedometer), and quaternion-calculation. Only tested on ARM-based Arduino boards ([SparkFun SAMD21 Mini Breakout](https://www.sparkfun.com/products/13664), [SparkFun 9DoF Razor - M0](https://www.sparkfun.com/products/14001)

Repository Contents
-------------------

* **/Firmware** &mdash; An Arduino library with an example that sends raw sensor data, quaternions, and AHRS data out of the serial port
* **/Hardware** &mdash; All Eagle design files
* **/Production** &mdash; Test bed files and production panel files

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_MPU-9250-DMP_Arduino_Library)** - Arduino library for the MPU-9250 Breakout.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/mpu-9250-hookup-guide)** - Basic hookup guide for the MPU-9250 Breakout.
* **[SparkFun Fritzing repo](https://github.com/sparkfun/Fritzing_Parts/blob/master/products/13762_sfe_imu_sensor_9250.fzpz)** - Fritzing diagrams for SparkFun products.

License Information
-------------------
The hardware is released under [Creative Commons Share-alike 4.0](http://creativecommons.org/licenses/by-sa/4.0/).  
The firmware is released under the [Beerware license](http://en.wikipedia.org/wiki/Beerware).
