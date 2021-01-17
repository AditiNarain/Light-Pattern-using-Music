# Light Pattern using Music
  ## Abstract:
In our project creating light pattern with diffrent colours using high and low pitch of sound. This uses a sound sensor which will turn on and off led by creating a pattern. 
### Components:
1.	Sound Sessor
2.	Arduino UNO
3.	LED
4.	Resistor 220 ohm
### About Component:
   #### • Sound Sensor:
  Sound sensor detects sound intensity same way as human diaphragm works and converts it to electrical energy. It consists of a microphone, a voltage comparator                   IC, a potentiometer, a transistor, couple of LEDS and a few other passive components (resistors and capacitors).The microphone detects the sound, then                           amplified. The voltage is compared by op amp as we set the threshold voltage.
  Operating Voltage = 3.3 to 5v
  
### Circuit Diagram:

![CircuitDiagram](https://user-images.githubusercontent.com/73650233/104852827-0f477200-5923-11eb-83f7-8ec47df4dbf1.jpg)

### Working: 
As we know sound pitch in the music goes up and down. We set a particular threshold value accordingly when sound intensity goes above that threshold value then ‘1’
signal is sent to the controller and if again the intensity is below threshold it gives ‘0’  to the controller which keeps on changing according to the music. Simultaneously with thishigh and low signal which controller is receiving is giving high and low output repeatedly. As we have connected different colours led so different colour are also being showing.

![Circuit_Diagram](https://user-images.githubusercontent.com/73650233/104852842-1cfcf780-5923-11eb-8b1a-2919a6d8ab11.jpg)

 Hence a beautiful pattern is being generated with the change is music intensity 
	Firmly do all the connection and upload the program to arduino uno. 



### Program Logic:
  
	if value == 1)
	  led 1 led2 on and led 3 led 4 off
	else
	  led 1 led 2 off and led 3 led 4 on

  If we have to chnage led intensity according to the sound then we can use pwm pin of arduino, so different intensity lights pattern can be generated. 

### Application:
  1. Music Lamp:A speaker with lamp which produces a light pattern on playing music.
  2. Noise Detector:When we have to check if the classroom is making noise or not.
  3.Traffic Noise controller:To reduce noise pollution when there is loud noise it will detect and measure can be taken.
  4. Door Alarm
