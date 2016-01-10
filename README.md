The source code for Odyssey TRX proect.

Was compiled with Altera Quartus II 13.1 Web Edition for EP4CE22F17.

For changing IP-address edit the ethernet.v 100-103's lines. Second receiver will IP + 1.

For programming the board use Altera Quartus Programmer (185Mb) https://cloud.mail.ru/public/FnG7/upFZCZNMT
and Altera Byte Blaster hardware http://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20160110085258&SearchText=usb+blaster

Version history:
1.0.0	– 11.08.15 - First base version
1.1.0	– 11.09.15 - Added automatic key and expanded protocol to support key control that work with Odyssey Key Master
1.1.1	– 03.10.15 - A few bugs fixed:
       -	Incorrect work of PTT in straight key mode
       -	Incorrect work of the Demo mode
1.1.2 – 22.10.15 - PTT control signal is now straight, not inverted; control connector pinout was also changed 
1.2.0 – 26.10.15 - openHPSDR protocol is supported
1.2.1 – 28.10.15 - openHPSDR protocol bug fixes, SNDP support has been removed
1.2.2 – 19.11.15 – was added stereo output in Headphones
1.3.0 – 6.12.15 -  was added the second independed receiver  

