# modem

Modem is more than a sample sketch for panStamp. This code is in fact used by almost any panStamp module connected to a serial (UART) host.

This application transfers to the UART port any packet received from the wireless network. At the same time, the host can control the modem via AT commands and transmit wireless packets through the modem. The serial protocol and AT commands are described [here](https://github.com/panStamp/panstamp/wiki/Modem%20and%20serial%20protocol)
