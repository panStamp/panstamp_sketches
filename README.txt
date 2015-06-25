Basic applications for panStamp.

1. simpletest : basic "blink a LED" application.

2. basicbeacon : Basic wireless beacon transmitter.

3. basicradio : Basic bi-directional application that pairs with another
   basicradio node and toggles an LED whenever a packet is received.

4. modem : Serial wireless modem that interfaces between a network of panStamps
   and a serial port (RS232, USB, ...). This application is used as the modem for
   all computer applications developed for panStamp.

   Description of the serial (ASCII) protocol:
   https://github.com/panStamp/panstamp/wiki/Modem%20and%20serial%20protocol

5. aesencryption : use of the hadware AES-128 encryption engine available
   on the CC430 MCU (panStamp NRG only).

6. ctrencryption : CTR-cypher algorithm on top of the basic AES-128 encryption
   (panStamp NRG only).


