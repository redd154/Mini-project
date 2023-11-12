
Health Monitoring System

Health monitoring systems are devices or applications that collect and track health data, such as heart rate, blood pressure. The Health Monitoring uses most of IOt like using both hardware and software. Here is the brief steps on working of Health Monitoring System:

Here is a more detailed description of each step:

The patient places their finger on the sensing unit. The sensing unit contains sensors that measure the patient's heart rate, vitals, and body temperature.
The sensors send the data to the Arduino Uno in the form of signals. The Arduino Uno is a microcontroller board that can process the data from the sensors.
The Arduino Uno processes the data and sends it to the Wi-Fi module. The Wi-Fi module is a device that allows the Arduino Uno to communicate with the smartphone application.
The Wi-Fi module transmits the data to the smartphone application. The smartphone application is a software program that runs on the patient's smartphone.
The smartphone application displays the data. The smartphone application displays the patient's heart rate, vitals, and body temperature on the smartphone screen.
The smartphone application sends an alert message if the sensed rate is more than the desired rate. The sensed rate is the current reading from the sensors. The desired rate is the normal range for the patient's heart rate, vitals, and body temperature.
Processing Data through Arduino UNO
The Arduino Uno processes the data from the sensors by converting the analog signals from the sensors into digital signals. The Arduino Uno then uses the digital signals to calculate the patient's heart rate, vitals, and body temperature.

Temperature conversion:

Temperature in degree Celsius, Temp = Output voltage * 0.4882812
This formula converts the output voltage from the temperature sensor into degrees Celsius. The output voltage is a measure of the amount of electrical current that is flowing through the sensor. The conversion factor of 0.4882812 is a constant that is specific to the temperature sensor.






## Acknowledgements


http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6892762&newsearch=true&queryText=gsm%20health

https://www.circuitstoday.com/interface-gsm-module-with-arduino

https://www.electroschematics.com/heart-rate-sensor/

https://www.circuitbasics.com/how-to-set-up-an-lcd-display-on-an-arduino/ 
## Documentation

[Documentation](https://linktodocumentation)

https://docs.google.com/document/d/13_AU-pRXnz37UnwkGTstdqbHISH_urjjb5IRCLulq2k/edit#heading=h.gjdgxs
## Tech Stack

**Client:** Temperature Sensor,Pulse Sensor,Moisture Sensor

**Server:** Arduino UNO


## Lessons Learned

The main insight I learnt from performing this project are about functioning of sensors and their significance by using the sensors I explore the different terms .The challenge faced by it is collection of sensors and making sure that it is properly working and I tackled this by knowing to protect it from damage as the sensors also involved programming by performing this project helped me in  developing  my programming skills. 

