# USB serial multiplexer

A device for using a single USB port to communicate with multiple serial targets.

## Credit

This board was created by Toby Makins, but based heavily on the Arduino-usbserial firmware by Arduino and Dean Camera.  Licensed under the MIT license. 

## Intended use

The intended use is for programming multiple devices with one USB port. A header is first sent to the Atmega16U2 indicating the device to be written too, which in turn causes the muliplexer to switch the UART output to the correct Tx/Rx/Reset lines. 

A binary file can then be written as normal with any serial port progammer. 

## WIP

The firmware of this device is still a WIP
