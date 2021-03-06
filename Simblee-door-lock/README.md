# Simblee-Door-Lock

Automated door lock with bluetooth connection.

I am still working on this github and this readme file.

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YYNTYF69KT7P8)


## Contents
- [Introduction](#introduction)
  - [What it is](#what-it-is)
  - [How it works](#how-it-works)
  - [What is the simblee](#what-is-the-simblee)
- [Disclaimer](#disclaimer)
- [Videos](#videos)
- [Installation](#installation)
  - [Adding code](#code)
- [FAQ](#faq)
- [License](#license)
- [Sources and additional links](#sources-and-additional-links)

## Introduction ##

### What it is

It's a simple door motorize door lock. It's a motor connected to the door dealbolt. When you press a button  before leaving your house, it will automatically close the door while you leave.

### How it works

The module is deepsleep mode. When you press the button, it will wake up and then wait for the door to close. The accelerometer will detect the impact of the door closing and then the module will active the motor.

### What is the simblee

The [Simblee](https://www.simblee.com/) is a bluetooth [Arduino](https://www.arduino.cc/en/Main/Software) like microcontroller. The magic is that you can write very life like iOS and Android app directly inside the [Arduino](https://www.arduino.cc/en/Main/Software) IDE.


## Disclaimer

Jerome Demers (Robomaniac) has made every attempt to ensure the accuracy and reliability of the information provided on this page. However, the information is provided "as is" without warranty of any kind. Jerome Demers (Robomaniac) does not accept any responsibility or liability for the accuracy, legality, content, completeness or reliability of the information contained on this page.


## Videos
  
[![Simblee Quick Start Guide](https://img.youtube.com/vi/_8l2ziZgdps/0.jpg)](https://www.youtube.com/watch?v=_8l2ziZgdps)
 
## Installation ##
### Code 


**2** Customize the code for your wiring.  
		here is code exemple  

		  //include the library you need
		  #include "simblee.h"

		  //button pins
		  #define up D1
		  #define down D2




## FAQ

**Is this an amazing question?**

Yes, but more are coming.

### If you have other questions or problems with the Simblee, you can also check out the official [community forum](http://forum.rfduino.com/index.php?topic=1066.0).

## License

This project is licensed under the MIT License - see the [license file](LICENSE) for details.

## Sources and additional links

Sparkfun tutorial: https://learn.sparkfun.com/tutorials/simblee-concepts/setting-up-arduino

Open servo: https://openservo.org/

Simblee: 
* https://www.simblee.com
