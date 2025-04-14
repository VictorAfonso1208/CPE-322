# Lab 5
## Overview
The purpose of this lab is to learn the usage of PahoMQTT and how to publish information from terminals and suscribe to other terminals.

To begin this lab, I had to first install mosquitto and pahomqtt onto my laptop.
![mosq](https://github.com/VictorAfonso1208/CPE-322/tree/main/Labs/Lab5/Lab5%20Images)
![paho](https://github.com/VictorAfonso1208/CPE-322/tree/main/Labs/Lab5/Lab5%20Images)

I then updated my copied Kevin Lu IOT directory using git pull:
![pull](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab5/Lab5%20Images/git%20pull.png)

I then ran pubcpu.py from the lesson 5 directory, which pulled date and time info from the mqtt client API, as well as my device's CPU usage.
![pub](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab5/Lab5%20Images/pubcpu.png)

Finally, I ran the subcpu.py in a separate terminal, which subscribed to the first terminal and published the same information.
![sub](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab5/Lab5%20Images/subcpu.png)

## Conclusion
This lab taught the basics of publishing API information from a terminal and establishing communication (through subscribing) from a different terminal.
