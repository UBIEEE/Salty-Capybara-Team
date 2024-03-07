# Salty-Capybara-Team  

## Our Components  

* [ARDUINO UNO R4 MINIMA](https://www.digikey.com/en/products/detail/arduino/ABX00080/20371542)
* [DC Gearbox Motor - "TT Motor" - 200RPM - 3 to 6VDC](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3777/8687221)
* [Adafruit DRV8833 DC/Stepper Motor Driver Breakout Board](https://www.adafruit.com/product/3297)
* [Lithium Ion Polymer Battery - 3.7v 1200mAh](https://www.adafruit.com/product/258?gad_source=1&gclid=Cj0KCQjwy4KqBhD0ARIsAEbCt6jXzDKFZ9s2u1SWslHxj_pmHKfOvDnqfYjc1EqkqUuEZbM6-pj9eD4aAlzkEALw_wcB)
* [JST PH 2mm 4-Pin to Male Header Cable - I2C STEMMA Cable - 200mm](https://www.adafruit.com/product/3955)
* [Adafruit Micro-Lipo Charger for LiPoly Batt with USB Type C Jack](https://www.adafruit.com/product/4410)
* [Linear Voltage Regulator IC Positive Fixed 1 Output 800mA TO-220](https://www.digikey.com/en/products/detail/stmicroelectronics/LD1117V33/586012?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Medium%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20223376311_adg-_ad-__dev-c_ext-_prd-586012_sig-Cj0KCQjwy4KqBhD0ARIsAEbCt6ibgO35ZWxodiH8e7t-dVcD3Mk_iP7YyMoJ_GBVjmCk-Ivfm1AZD1EaAr--EALw_wcB&gad_source=1&gclid=Cj0KCQjwy4KqBhD0ARIsAEbCt6ibgO35ZWxodiH8e7t-dVcD3Mk_iP7YyMoJ_GBVjmCk-Ivfm1AZD1EaAr--EALw_wcB)
* [Adafruit VCNL4020 Proximity and Light Sensor - STEMMA QT / Qwiic](https://www.adafruit.com/product/5810)
* [Adafruit LSM6DSOX 6 DoF Accelerometer and Gyroscope - STEMMA QT / Qwiic](https://www.adafruit.com/product/4438)
* [STEMMA QT / Qwiic JST SH 4-pin to Premium Male Headers Cable - 150mm Long](https://www.adafruit.com/product/4209)
* [Ultrasonic Distance Sensor - 3V or 5V - HC-SR04 compatible - RCWL-1601](https://www.adafruit.com/product/4007)
* [THIN WHITE WHEEL FOR TT DC GEARB](https://www.digikey.com/short/85b98tj9)  

## Libraries

* [Arduino_LSM6DSOX](https://www.arduino.cc/reference/en/libraries/arduino_lsm6dsox/)
* [Adafruit VCNL4020](https://www.arduino.cc/reference/en/libraries/adafruit-vcnl4020-library/)
* [CDRV8833](https://www.arduino.cc/reference/en/libraries/cdrv8833/)
* [HCSR04 ultrasonic sensor](https://www.arduino.cc/reference/en/libraries/hcsr04-ultrasonic-sensor/)  

## Todo  

* Have working algorithm(s)
* Create code for sensors
* Have the electronic-mechanic relationships work
* Create chassis
* Put together robot physically

## Milestones (Updated as of 3/7)


### Milestone Set 1: March

#### Weeks 1 & 2
* Worked on Arduino Ultrasonic sensor. 
Sensor can:
  * Detect how far an object is based on where it is.
  *  I need to work on GPIO Output

#### Week 4 (had spring break)
* Get the algorithm working in simulation. 
* Positioning algorithm can properly visualize mouse in simulation.
* Can make the motors spin from the battery.
* Microcontroller can control the motors. 


### Milestone Set 2: April

#### Weeks 1 & 2
* Microcontroller can read sensor data and calculate the position of the mouse.
* Microcontroller can run the algorithm.  

#### Week 3
* Mouse can move in a straight line a stop when it reaches an obstacle.
* Mouse can turn 90 degrees when told to by the algorithm.
* Mouse can move for 10 minutes straight. 
* Mouse can execute different algorithms based on user inputs from physical buttons on the mouse.

#### Week 4  
* Mouse can move through a maze randomly without hitting walls.  


### Milestone Set 2.5: May - Week Prior to Finals Week
* Mouse can solve a predefined maze.
* Mouse can solve randomly generated mazes.
