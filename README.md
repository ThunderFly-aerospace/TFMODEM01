# TFMODEM01A -  ThunderFly ground station radio telemetry system

The modem is part of the ThunderFly ground control station technology. It is supposed that TFMODEM is paired with [TFSIK](https://github.com/ThunderFly-aerospace/TFSIK01) telemetry transceiver on the remote vehicle (UAV/UAS). The remote device should run our port of widely-used [SiK firmware](https://github.com/ThunderFly-aerospace/SiK), which is ported to an upgraded Si1060 SiliconLabs chip. Although this new chip supports new features, the TFMODEM is also backward compatible with older SiK devices.

![Modem front](doc/img/TFMODEM01A_front.jpg)

## Features

  * High noise immunity against out-of-band jamming attempts or noise
  * Capability to use multiple antenna types with automatic antenna selection and switching (User could use the directional and omnidirectional antenna at once. The modem selects the best automatically)
  * Spectral analyzer feature could help users select the best [TFSIK](https://github.com/ThunderFly-aerospace/TFSIK01) hardware frequency band to avoid jamming and increase the link reliability. 

The modem could be extended up to four antenna MIMO  RX/TX configurations by adding the external RF switch network (optional extension device). This feature could be useful in use cases where antenna rotators with highly directional antennae are impractical. 

<p float="left">
<img src="doc/img/TFMODEM01_schematics.png" width="45%" />
<img src="/doc/img/TFMODEM01_multi_antenna_extension.png" width="45%" />
</p>

## Technical Highlights

  * Supported protocol: MAVLink 2
  * Supported bands: 433MHz, 868 MHz or custom-requested frequencies
  * User-selectable output power up to +20 dBm
  * RX Sensitivity -124 dBm @ 1000 bps FSK
  * MIMO RX/TX: 2 Antenna as standard (more antenna MIMO is optional)
  * Interface: full-speed USB 2.0 USB-B
  * RF switch: SPDT High Power UltraCMOS 10 MHz - 3 GHz
  * RF input amplifier
    * 50MHz to 4000MHz, GaAs pHEMT SPF5189
    * Noise Figure 0.60dB
    * High noise immunity OIP3 39.5dBm
    * Gain 18.7dB
  * Filter: SAW AFS selected for specific ISM band
  * Power: USB +5V 500 mA.

## Where to get it?

ThunderFly ground control station telemetry modem is commercially available from [ThunderFly s.r.o.](https://www.thunderfly.cz/), write an email to info@thunderfly.cz or shop at [Tindie store](https://www.tindie.com/products/thunderfly/tfmodem01-sik-telemetry-ground-station-unit/).


