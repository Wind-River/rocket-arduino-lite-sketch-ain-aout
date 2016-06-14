## Wind River Rocket [**Arduino-lite**](https://github.com/Wind-River/rocket-arduino-lite) API

# Arduino-lite Analog Sensor I/O Sketch
An analog input (**Potentiometer**, **Sound**, or **Light** sensor) controls a PWM output (to **buzzer** or **LED**)    

***  


##  Required Hardware
 * [**Intel Galileo Gen 2**](http://www.intel.com/content/www/us/en/embedded/products/galileo/galileo-overview.html) or [**NXP FRDM-K64F**](http://www.nxp.com/products/software-and-tools/hardware-development-tools/freedom-development-boards/freedom-development-platform-for-kinetis-k64-k63-and-k24-mcus:FRDM-K64F)  
 * [**Grove Starter Kit**](http://www.seeedstudio.com/deled/Grove-Starter-Kit-for-Arduino-p-1855.html)
   * Input sensor (connected to **A0**).  Choose one of **Potentiometer**, **Sound**, or **Light** sensor
   * Output sensor (connected to **D6**).  Choose One of **Buzzer** or **LED Socket Kit** with **LED**
 
## Hardware Configuration

1. Power off the **Intel Galileo Gen 2** or **NXP FRDM-K64F** before connecting shield or sensors  

2. Ensure that the **VCC** switch on the **Grove Shield** is appropriate for the device:  
* **5V** for the **Intel Galileo Gen 2**; or   
* **3.3V** for the **NXP FRDM-K64F**. 

3. Choose one of the 3 input sensors (**Potentiometer**, **Sound**, **Light**) and insert one end of a 4-pin cable into the connector.

4. On the Grove Shield, locate the connector labeled **A0** and insert the other end of the 4-pin cable.

5. Choose one of the 2 output sensors (**Buzzer** or **LED Socket Kit**) and insert one end of a 4-pin cable into the connector.

6. If you are using the **LED Socket Kit**, choose one of the LEDs and insert the two wires into the socket of the **LED Socket Kit** sensor ensuring that the  **anode (long wire)** is in the **positive (+)** socket.

7. On the Grove Shield, locate the connector labeled **D6** and insert the other end of the 4-pin cable.


## Control and Output
### Input
1. **Potentiometer**: Turn the dial slowly left and right  
2. **Sound** sensor: Clap your hands near the **Sound** sensor; or    
3. **Light** sensor: Cup your hand over the **Light** sensor, varying the light reaching the sensor

### Output
1. **Buzzer**: The frequency of the **buzzer** changes based on the input; or  
2. **LED Socket Kit**: The intensity of the **LED** changes based on the input.


