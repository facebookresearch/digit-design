# DIGIT Programmer

A tool to allow flashing new firmware to the DIGIT device

This utility allows for downgrading or upgrading firmware, as well assigning a device serial number.

## Installation
Clone the repository and install the package using:

	git clone https://github.com/facebookresearch/digit-design.git
	cd digit-design/firmware/digit-programmer
	pip install -r requirements.txt

This tool also requires ```dfu-util```, install with:

    $ sudo apt install dfu-util

### Adding DIGIT and DIGIT-PROGRAM udev Rule
Add your user to the ```plugdev``` group,

    adduser username plugdev

Copy udev rule,

    sudo cp ./udev/50-DIGIT*.rules /lib/udev/rules.d/

Reload rules,

    sudo udevadm control --reload
    sudo udevadm trigger
    
Replug the DIGIT device into host.

### Firmware Download
The current public firmware release is found in the ```digit-design``` respository. 


## Usage
To upload firmware to the DIGIT device specify the path to the binary firmware file and the device's serial number (trailing zeros and D prefix is not required).

Default firmware binary file name is specified in ```programmer.yaml```.

Flashing DIGIT device with serial number ```D00045```,

    $ python3 flash.py digit.serial=45

Flashing DIGIT device with alternate firmware binary,

    $ python3 flash.py digit.firmware="digit-development.bin" digit.serial=45







