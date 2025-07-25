# LoRa_experiments

This repository contains the results of a series of experiments that were performed using the Reyax RYLR998 LoRa module.
The Reyax RYLR998 is an inexpensive LoRa "modem".  It can perform point to point wireless data communication with other such modules.
The RYLR998 contains both a LoRa chip and a low power microcontroller.  A host microcontroller communicates with an RLYR998 using
serial port "AT" commands, making the RYLR998 very easy to use.  In addition, the RYLR998 has a low power sleep mode that reduces current
draw to about 10 microamps.  The use of LoRa for long distance, low volume data communication along with the ability to sleep the module
when not transmitting suggests that these modules could be ideal for use as long range contact open/close sensors.

Our test results were very positive, leading to the development of deployable hardware and software.  This repository contains detailed information
about a complete system, consisting of:

1. Low power, battery operated LoRa contact sensors.

2. Non-low power version of the LoRa sensors that are suitable for gathering and logging detailed range testing data.

3. An Internet connected Hub that communicates with the LoRa sensors.

4. Other components that create a complete, integrated LoRa-based sensor system.

This repository also memorializes earlier protoype hardware and software that was used in the incremental testing and development of the deployable
hardware and software.

A complete overview of the project and of this repository is contained in the document:

"LoRa_Experiments_Overview_Document".

Note that this repository is not a complete project in and of itself.  However, it contains open-source details of the hardware and
software that are used in subsequent, deployed projects.  These latter projects are documented in their own repositories that reference
the designs documented herein.
