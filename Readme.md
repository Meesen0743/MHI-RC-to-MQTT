#Mitsubishi Heavy Industries Superlink to MQTT Project for Cloudless home automation

For the use with units supporting the use of the Rc-Ex Controllers
MQTT as an open source option that will easily integrate with HomeAssistant (Hassio)

Key notes / Findings:
---------
* 2 wire XY Bus operating at +17v (+14v reported in some documentation)
* Super Link uses MHI’s own protocol, including collision detection (CSMA/CD) system
* SL (Superlink) operates at 9600 bps, SL2 (Superlink 2) at 38400 bps both with a RS-485 interface


Resources:
---------
* https://www.mhi.co.jp/technology/review/pdf/e452/e452006.pdf
* https://www.intesishome.com/docs/IntesisHome_MH-RC-WIFI-1_Compatibility_List.pdf  
* https://www.home-assistant.io/integrations/climate.mqtt/



About myself: 
---------

I work as an Automotive Installer with limited programming knowledge 
I'm hoping to find others interested in this project and that with their added 
knowledge can help to get a working prototype that doesn't rely on expensive cloud based solutions offered on the market.
