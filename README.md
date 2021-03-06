SparkFun9DOF
============
Read from [SparkFun 9 Degrees of Freedom](https://www.sparkfun.com/products/13033) Edison board. Sensors are read and a Signal is notified each time a Signal is processed by the block. For more info on the LSM9DS0 view the [datasheet](http://www.st.com/web/en/catalog/sense_power/FM89/SC1448/PF258556).

Properties
----------
None

Inputs
------
- **default**: Any list of signals to trigger sensor read.

Outputs
-------
- **default**: A list of signals with the following attributes: accelerometer, magnetomoter, gyroscope, temperature.

Commands
--------
None

Dependencies
------------
-   [**mraa**](https://github.com/intel-iot-devkit/mraa): Not on PyPI. Follow the install instruction on [sparkfun](https://learn.sparkfun.com/tutorials/installing-libmraa-on-ubilinux-for-edison)
-   [**numpy**](https://pypi.python.org/pypi/numpy)


Output Example:
---------------
```
{
  accelerometer: tuple of (x, y, z),
  magnetometer: tuple of (x, y, z),
  gyroscope: tuple of (x, y, z),
  temperature
}
```

