                             _      _ _     
                            | |    (_) |    
   ___ _ __ ___   ___  _ __ | |     _| |__  
  / _ \ '_ ` _ \ / _ \| '_ \| |    | | '_ \ 
 |  __/ | | | | | (_) | | | | |____| | |_) |
  \___|_| |_| |_|\___/|_| |_|______|_|_.__/ 

Arduino Energy Monitoring Library - compatible with Arduino 1.0 
***********************************************

Designed for use with emonTx: http://www.openenergymonitor.org/emon/emontx

Initially forked from https://github.com/openenergymonitor/EmonLib in order to:

 -> add support for 12-bit ADC resolution on Arduino Due.

 -> add 3-phase buffer-delay algorithm, when CT sensors connected to different line phases.


Download to Arduino IDE 'libraries\EmonLib_3PH' folder. Restart of IDE required.

Git Clone and Git Pull can be easily used to keep the library up-to-date and manage changes. JeeLabs has done a good post on the topic: http://jeelabs.org/2011/12/29/out-with-the-old-in-with-the-new/

If using TortoiseGit, start Git Clone command with these parameters:
  URL: https://github.com/icboredman/EmonLib
  Directory: \Arduino\libraries\EmonLib_3PH
  Branch: [checked] feature/12bit_3phase
