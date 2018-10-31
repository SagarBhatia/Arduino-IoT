# Arduino-IoT
Project Name:- 'AIR CONTROL'

Air Pollution is the Main Problem nowadays which the World is Facing and Pollution is Increasing Gradually.
This Project is based on Controlling of Air. This Project won't only Monitor the Air but Control it.

This Project is FULLY AUTOMATED.

Hardware Components Required: 
1. NodeMCU ESP8266
2. Jumper Wires
3. Gas Sensor
4. Container
5. ServoMotor
6. Server and Database(Software)


Two NodeMCU ESP8266 Chips works as Sender and Receiver of Data

We had Attached the Gas Sensor to NodeMCU ESP8266 which gives the Current reading of Air  gases.

Now, One ESP8266 Chip will Send the Data to Server and Store in Database

AIR MONITORING part is Completed till the Data is Received on Server.

Now, the Another ESP8266 Chip will Fetch the Data from the Server and Analyse it.
 
The Another ESP8266 Chip is Connected to ServoMotor and ServoMotor is Attached to Container for Opening and Closing of Container
 
 The Container Contains Some Suitable Chemicals for Controlling of Air.
 
 When the Data Received Exceeds the Particular Gas Limit Instructs the ServoMotor to Open the Container
 
 As the Container Opens, the Chemicals Present inside the Container absorbs  the Gas and Reduce the ppm level present in Atmosphere
 
 When the ppm level decreases and comes under  the Particular Gas Limit, the ServoMotor Closes the Container
 
