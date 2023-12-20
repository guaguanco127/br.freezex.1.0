# Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live 

## br.freezex.1.0



By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)  
[https://www.brianriordanmusic.com/](https://www.brianriordanmusic.com/) 
  
Repository for br.freezex.1.0, with all related files, can be found here: [https://github.com/guaguanco127/br.freezex.1.0](https://github.com/guaguanco127/br.freezex.1.0)  
Additional programs can be found here: [https://github.com/guaguanco127/plugins](https://github.com/guaguanco127/plugins)

These files were created with Max/MSP version 8.5.6. 

## Links

[About](#About) 
[Ableton Max for Live Device](https://github.com/guaguanco127/br.freezex.1.0/tree/main/Ableton%20Max%20For%20Live) To use inside of Ableton Suite   
[Max/MSP Abstraction](https://github.com/guaguanco127/br.freezex.1.0/tree/main/MaxMSP%20Abstraction) To use as an abstraction within Max/MSP   


## <a name="About"></a>About

This is a spectral Max/MSP abstraction, and Ableton Max for Live device that allows the user to do a spectral freeze of a stereo signal. Additionally, a transient detector option is available. This contains all features available within the br.freeze.1.0 patches, except this version allows the user to crossfade into the next freeze betwee 50 ms and 10 seconds. 

Currently works in any sample rate or bit depth.

Only works as an abstraction or a device. External objects and RNBO not available yet. An extremely important file is included in each folder called "solofreeze.pfft" do not move or delete this file until you follow all instructions for installation. 
  
**Freeze:** On/Off, Bypass or Freeze.  
**Retrigger:** When the freeze is on, this will freeze the current stereo signal.   
**Crossfade:** Determines the duration of time it takes to crossfade from one freeze to the next. The lowest is 50 ms, the highest is 10,000 ms (10 seconds).  
**Mix Modes:** "Insert" interrupts the signal with the freeze, while "Gate" only allows the freeze to sound without passing through the dry signal during bypass.    
**Transient Detect:** When both "Freeze" and "Transient Detect" are on, the freeze will occur automatically based on the transient detection sensitivity settings. Detections cannot occur faster than 100 ms.   
**Transient Detect Sensitivity:** When both "Freeze" and "Transient Detect" are on, this will determine how sensitive the transient detection is. Between 0. and 1., 0. is lowest sensitivity, while 1. is the most sensitive. 
 