# arduino-libopenaptx

[![Arduino Library](https://img.shields.io/badge/Arduino-Library-blue.svg)](https://www.arduino.cc/reference/en/libraries/)
[![IDF Component](https://img.shields.io/badge/IDF-Component-blue.svg)](https://github.com/pschatzmann/arduino-libopenaptx)
[![CMake](https://img.shields.io/badge/CMake-Supported-blue.svg)](https://cmake.org/)

This is Open Source implementation of Audio Processing Technology codec (aptX)
originally derived from ffmpeg 4.0 project and licensed under GPLv3+. 

I converted https://github.com/pali/libopenaptx to an Arduino Library

## Installation

For Arduino, you can download the library as zip and call include Library -> zip library. Or you can git clone this project into the Arduino libraries folder e.g. with

```
cd  ~/Documents/Arduino/libraries
git clone https://github.com/pschatzmann/arduino-libopenapt.git
```
This has the advantage that you can easily get the latest code updates by just executing the command ```git pull```

## Documentation

I recommend to use this library together with my [Arduino Audio Tools](https://github.com/pschatzmann/arduino-audio-tools). 
This is just one of many __codecs__ that I have collected so far: Further details can be found in the [Encoding and Decoding Wiki](https://github.com/pschatzmann/arduino-audio-tools/wiki/Encoding-and-Decoding-of-Audio) of the Audio Tools.

## Licence

Please read the [license information of the orignal project](README.orig)


