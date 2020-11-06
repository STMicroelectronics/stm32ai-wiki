
# Human activities dataset

This is a sample dataset of human activities built for educational purposes.
The dataset contains 3-axis accelerometer data collected using the STM32L4 Discovery kit IoT node (B-L475E-IOT01A) development board.
Acceleration data is stored in comma-separated values (csv) files.
Each line corresponds to a 3-axis reading with the x, y and z axis numeric values.

## Associated activity classes

* stationary - the person is either sitting on a chair at a desk or standing upright without moving. Some data has also been captured with the device placed, at rest, on a desk.
* walking - the person is walking in a straight line with some occasional changes of directions.
* running - the person is running.

## Sensor locations

During data acquisition, the board was placed around the wrist, in the hand, over the arm or in the pocket.

## Sensor configuration

* Sampling rate: 26 Hz
* Range: [-4000 mg; 4000 mg]
* Sensor: LSM6DSL

## Changelog

### v1.0.1 - September 23, 2020

* Set license to BSD-3 Clause.

### v1.0.0 - April 9, 2020

* Initial dataset.

## Author

STMicroelectronics - Artificial Intelligence Solutions (AIS) Team

## License

This work is licensed under the [BSD 3-Clause License](opensource.org/licenses/BSD-3-Clause).
