# RP2040_ServoWatch

The Links: 
* **The Hardware:** 
* https://www.amazon.com/dp/B0C4PM196G?ref_=cm_sw_r_apan_dp_PKQF9GHS61ZPJYZ71R9G&amp;th=1
* (Mainly Picked cause of all of the on-board sensors, cause its an RP2040 on board, and Type-C. AND is capable (with an adapter that comes with it, cable) GPIO as well. (When/If I want to make a smart watch, this SHOULD be everything I need EXCEPT for wireless, which a module can be added in IF deamed nessisary
*   * ...lowkey would look cool if I just whipped out my watch out of a secret compartment a bunch of wires that I plug into something and just, take control over it B) [not the goal, but you see my idea about modularity and further expanding in the design B) ...maybe even pre-made cartrages to ensure pins allign well, idk LMAO)  
* Amazon Name: waveshare RP2040 MCU Board with 1.28inch Touch Round LCD 240x240 Pixels 65K Colorful IPS LCD Display for Clear Color Pictures,Based on Raspberry Pi RP2040 Dual-Core Arm Cortex M0+ Processor


* **The Software: **
* https://www.waveshare.com/wiki/RP2040-Touch-LCD-1.28#Demo
 * This is the Main DEMO that is believed to be on the board itself when it arrives in the box. SHOULD demo the Gyro, Accelerometer, some Jap/Chinese Symbols @ the top, and a "battery" voltage output (I am currently just using a Type-C cable, so this is not very helpful atm)
 * HOPING the above zip file (Containing Arduino, C, AND YES, PYTHON [idk if its circuitpython or micropython]) works first try, cause otherwise, I just lost the demo project forever (not properly showing up in Thonny, etc etc, for me to be able to extract it directly off the board :/ )

* 
-----------
Current plan is, Due to me literally not @ my parents house not having another microcontroller / Raspberry-Pi-like device (let alone an arduino) lying around and I got this today....

I plan to: 

* Control 2 Servos, configured in a Pan-Tilt Configuration
* See if I can get the touch-screen to work
  * Display
  * Touch
* Any of the on-board sensors
  * Gyro
  * Accelerometer

(GPIO Pinouts are listed on the link above) 

