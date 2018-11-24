# IncomingCallDetector
Based on circuit from http://www.circuitstoday.com/mobile-incoming-call-indicator
PCB created by David Story and David House for soldering workshop.
![alt text](https://github.com/david-story/Incoming-Call-Detector/blob/master/resources/board.png)


### General
PCB created in Eagle for a small incoming call detector for your cellphone. This board was created to help teach students introductory soldering with through-hole components. There will be another repository shortly with a board for SMD soldering practice.

The circuit for this board works by having the board placed near your cell phone. While your phone is place on silent, the transmitter of the phone will still be activated, and will produce a frequency of around 900 MHz. The circuit will pick this up with its 10 uH coil, and the signal will be amplified, illuminating an LED to give you a visual indication that your phone is buzzing. <a href="http://www.circuitstoday.com/mobile-incoming-call-indicator">[1]</a>

### Dependencies
No dependencies, uses standard Eagle Library parts. Creating in Eagle Version 9.2.2 Education

### Installation 
1) Download files either from site or by using git clone https://github.com/david-story/IncomingCallDetector.git
2) Open project file
3) Done
