# Z3 Roller Shutter
This repository holds documentation and implementation on how to create a Zigbee 3.0 Standard roller shutter  

In order to proceed, you will need to download EmberZNet SDK through Simplicity Studio
The SDK's access can only be requested using the serial number coming from this development kit :
[SLWSTK6000B](https://www.silabs.com/development-tools/wireless/zigbee/efr32mg-zigbee-thread-starter-kit)

At the time of writing, this is done using Simplicity Studio v4 and GSDK 2.7.8

{% include list.liquid all=true %}

## Description ##
This implementation runs a Roller Shutter on a BRD4161 radio board
It can be used alone (no gateway) or with [that gateway implementation](https://github.com/brian-silabs/Z3_GatewayHost)

To pair and use it, follow the steps described in the section *"Running the example"*

## Documentation ##

Official documentation can be found at our [Developer Documentation](https://docs.silabs.com/zigbee/latest/) page.

## Disclaimer ##

The Gecko SDK suite supports development with Silicon Labs IoT SoC and module devices. Unless otherwise specified in the specific directory, all examples are considered to be EXPERIMENTAL QUALITY which implies that the code provided in the repos has not been formally tested and is provided as-is.  It is not suitable for production environments.  In addition, this code will not be maintained and there may be no bug maintenance planned for these resources. Silicon Labs may update projects from time to time.
