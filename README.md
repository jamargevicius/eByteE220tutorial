# eByteE220tutorial
This tutorial brings one through the use of the eByte E220 transmit/receive module, with the ESP32 microcontroller Development board. The reason for use of the eByte device is to allow very low power consumption by a remote Rx.  

There are 9 sections, starting with basic wiring up and testing of the Tx and the Rx setup. After going through testing of Tx <--> Rx basic communication, the tutorial considers a setup with the Rx ESP32 going to sleep, then a setup with the Rx/Tx implementing a Wake-on-Receive (WOR) mode, then a combined sleep/WOR mode, then adding reliability in the "somewhat" unreliable eByte device.  Finally, the 9th section implements a "Something Useful" design that has the local Tx providing web serving to a browser, and the Rx responding to commands to turn on/off an LED on the remote Rx. 

There is a pdf file that is the tutorial explanation, and there is a zip file which contains the main.cpp programs for each of the 9 sections (labeled A --> H).
