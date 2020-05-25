# Intelligent-Interactive-Products
A project for the TU/Eindhoven. Made by Industrial Design students. 

# Introduction
This project is part of the Interactive Intelligent Products course at the TU/e which challenges students to create a smart product in a matter of weeks. Learning them how to use sensors and self-learning models to create and interactive and intelligent system. 

In this specific example, we have made a tool which estimates the moment your plants need watering by checking the soil and air humidity and the temperature. By using a regressor model, several datasets and some time, this system can inform the user via a screen when it expects the plant needs watering. 

This first model is a very first iteration, used to learn the very basics of this new skill. 

# Arduino and Processing 

## Arduino
Arduino software is used to control the Arduino microcontrollers. Downloading the Arduino IDE can be done via (this website)[https://www.arduino.cc/en/main/software]. If you have any issues or wish to have more information on how to use and program your Arduino, please take a look at (their guides)[https://www.arduino.cc/en/Guide/HomePage]. 

The Arduino programs in this repository have been created to be used on an Arduino Nano, but should work on most Arduino microcontrollers. 


## Processing
Processing is a type of sketchbook software, often used to visualise data. It can be used to do this via the serial connections. Downloading processing can be done (here)[https://processing.org/download/]. For any additional information or help, please read the (tutorials)[https://processing.org/tutorials/] or use the (reference)[https://processing.org/reference/].


# Files in this repository 
The files in this repository are made for Arduino and Processing, and can be used for the following things. 

## Arduino - Sensor Test Code 
This program can be uploaded to your Arduino and used to check if your sensors work and what values they give in the monitor. This is useful when you want to finetune the mapping of your hygrosensor by checking the printout. 

## Arduino - Sensor Data to Processing 
This program can be uploaded to your Arduino and used to send the data from the sensors to Processing for further usage. The data is labeled, and send to Processing via the serial connection 

## Processing - Showing Data Stream
This Processing program can be used to check if the data is coming in from the Arduino by visualising it in several data streams which update in real time. 

## Processing - Saving the Data from Arduino 
Finally, this program can be used to save the data that is coming in through the serial connection. You can edit the amount of datapoints you wish to save, and give different datasets different labels while collecting the data. 

