# SmartEntry

## Description of the project

Cars entering the school using the ancient stickers were a concern since there had been many events regarding security. Our proposal was to use passive RFID tags integrated in stickers to identify cars in campus. At first, this may seem no different than a simple automation system. With a database deployed in a cloud system which can be monitored in real time, enables us to perform different operations using data obtained by RFID stations around the campus, like logging entries, setting alarms around prohibited zones and estimating empty parking spot count.

## Team Members

![](https://i.imgur.com/46yQxQF.png)
Left to Right:
* [Kayahan Taşyaran](https://github.com/ktasyaran) 
* [Ali Kaan Gündüz](https://github.com/alikaang) 
* Tuğçe Delipınar 

## Hardware setup
* RC522
* Raspberry Pi Model B
* Toggle Switch
* 5mm LED and resistors

## Schematic:

* [Schematic in PDF Format](https://github.com/bounIoT/SmartEntry/blob/master/Figures/Raspberry_Schematic.pdf)

![](https://github.com/bounIoT/SmartEntry/blob/master/Figures/raspberry_schematic.PNG)

## Flow of data 

![](https://github.com/bounIoT/SmartEntry/blob/master/Figures/DataFlow.PNG)

## Tools
* Operating System: [Raspbian](https://www.raspbian.org)
* Cloud: [IBM Bluemix](https://www.ibm.com/cloud/), [MLab](https://mlab.com)
* Database: [MongoDB v3.4.14](https://www.mongodb.com)
* Languages: JavaScript, HTML
* Development Environment: [Node-RED v0.18.5](https://nodered.org)
* System Configurations for each file existing in Repository


## Further References

* [Create a connection in MongoDB](https://www.compose.com/articles/power-prototyping-with-mongodb-and-node-red-2/)
* [Create GET-POST in Node-RED](https://www.compose.com/articles/5-minute-signup-with-node-red-and-compose/)
* Lab 1 (in Node-RED flow) and Lab 4 materials (UI Part) used in course [CmpE490](https://www.cmpe.boun.edu.tr/courses/cmpe490/2018/spring)
* [Reading RFID MiFare cards into Watson IoT Platform using your Raspberry Pi 3](https://developer.ibm.com/recipes/tutorials/reading-rfid-mifare-cards-into-watson-iot-platform-using-your-raspberry-pi-3/)
