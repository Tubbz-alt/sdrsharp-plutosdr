# sdrsharp-plutosdr

Analog Devices ADALM-PlutoSDR driver for SDR#

## Installation

### Windows

1. Copy the Release\SDRSharp.PlutoSDR.dll into SDR# installation directory
2. Install the [32bit build of libiio](https://wiki.analog.com/resources/tools-software/linux-software/libiio#libiio_installer_for_windows) on your system, or move the .dlls into the SDR# directory
3. Add the following line in the frontendPlugins sections of FrontEnds.xml file:

	&lt;add key="PlutoSDR" value="SDRSharp.PlutoSDR.PlutoSDRIO,SDRSharp.PlutoSDR" /&gt;


4. Launch SDR# and cross fingers :)

**Be aware that any update of SDR# will require you to follow again steps 2 to 4!**

## Thanks to 

Jean-Michel Picod for the bladeRF driver, which was used as a base for this driver
https://github.com/jmichelp/sdrsharp-bladerf


## Bugs? Ideas?

Please report them using the bugtracker on the Github project!
