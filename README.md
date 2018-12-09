# FLOOD PREVENTION SYSTEM

 
The Internet of things is defined as the inter-networking of physical Devices such as traffic lights, homes accessories, Industrial equipment, automobile or embedded items like sensors, actuators, software and create a system which enable the different object to collect, exchange or preform analytics over data that is connected to network. The IOT is the future of technology . As we all know that natural calamities are uncontrollable like floods, tornado, earthquake etc. but by the mean of technology we can control their devastated effects. Isn’t it fascinating we know before the flood and save our self’s and important utensils before it happens. This project “flood prevention system” basically a basic structure which identify the rise in the water level during the heavy raining outside and notify via email or message alert through network, So that the person have time to secure there utensils and prepare themselves before it happen. Although the use is not limited to this we can use this system anywhere where we have to deal with the water or any liquid level notification.

![alt text][pic1]

[pic1]:https://github.com/Gurbir0070/CS207PROJECT/blob/master/images/8d820caa-2ce7-47c1-8f99-f63acf0bd36e.JPG

# REPOSITORY CONTENT

images - this folder contains the images of project

code - here goes the code 

License - the license

readme - the file reading now 

# MATERIAL REQUIRED FOR PROJECT

	An Arduino Uno

	An ethernet SHIELD

	A FLEX sensor 

	A 10K ohm resistor

	A 1-inch fishing bobber

	Connecting wires

	A 9-Volt power supply to power Arduino and Ethernet Shield

	A web server running PHP 4.3  or higher


# ALGORITHM: -

	STEP1: - If the rainfall occurred 

	STEP2: - Sensor get activated, monitoring water level initiated  

	STEP3: - loop initiated 

	STEP4: - Analysing of new water level and send data for calculation.

	STEP5: - if the water level is above the prescribed level then

	STEP6: - Evaluating the threshold value and send the notification about flooding condition.

	STEP7: - Warning notification send via Wi-Fi network.

	STEP8: - Stop the System.


# WORKING

Attach wire and a resistor to the sensor leads end of flex resistor

Connect the Flex Sensor leads to the analog pin of an arduino

Write the  program for the Arduino that monitor the Changes in the flex sensor reading and trigger the event when large devation in the initial value

connect the ethernet shield to the Arduino so the sketch can communicate with a web server running PHP.

 Write a PHP Script that will get input value from Ardiuino. When the water level has changed ,and send the notification alert to recipient .




# TEAM
1.GURBIR SINGH DUTT

2.BAWANDEEP SINGH

3.PRABHDEEP SINGH
