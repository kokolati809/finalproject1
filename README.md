# finalproject1
Send an SMS with the ESP32 (Twilio)

What is your project? Sending SMS with the ESP32 (Twilio)
Why did you do this project? To demonstrate the varsity of ESP32.

Tools need
ESP32 
Twilio Account


Step 1
Get yourself a Twilio free trial account https://www.twilio.com/ 


Purchase a twilio phone number
Add a verified cell number to your account 
Setup the messaging service: on the left sidebar click on Messaging > Try it out > Get Set Up. Then, click on Start set up. 

Step 2

Install the twilio-esp32-client Library: Go to Sketch > Include Library > Manage Libraries. Search for twilio-esp32-client and install the library.









Include the twilio-esp32-client library. https://raw.githubusercontent.com/RuiSantosdotme/Random-Nerd-Tutorials/master/Projects/ESP32/ESP32_Send_SMS_Twilio.ino

Insert your network credentials on the following lines:
 
Insert your Twilio account details: the account SID and token, and the Twilio phone number.
 
Insert the recipient number and the message
 
In the setup(), initialize the Serial Monitor and connect the ESP32 to your local network so that it can get access to the internet and make the HTTP requests to send SMS.
 
Then call the send_message() function that accepts as arguments the recipient number, the sender number, the message, and a variable to hold the response.
 
 
