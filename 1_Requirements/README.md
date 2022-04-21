# PROJECT TITTLE - Password Based Door Lock Security System
## INTRODUCTION
  * Many times, we forgot to carry the key of our home. Or sometimes we come out of our home and door latch closes by mistake. In these cases, it is really difficult to get inside the house. This project is designed to solve this purpose. Main concept behind this project is of a door-latch opening using a password entered through keypad. As well as turning on the Buzzer when password is entered wrong. Today people are facing more problems about security in all over world, nowadays security is the most
essential issue everywhere in the world so security of everything gains higher and higher importance in recent years. The main component in the circuit is 8051 microcontrollers. Here, 4*4 keypad is used to enter the password. The entered password is compared with the predefined password. If it is correct password, the
system opens the door by rotating door motor and displays the status of door on LCD. If the password is wrong then door remains closed and displays ―password
is wrong on LCD. It can be used at organizations to ensure authorized access to highly secured places. With a slight modification by replacing the motor driver with a relay driver, this circuit can be used to control the switching of loads through code. This circuit can be also modified by using EEPROM chip interfaced to the microcontroller and store the entered password in the chip. Such an automatic lock system consists of electronic control assembly which controls the output load through a password. This output load can be a motor or a lamp or any other mechanical/electrical load.


## Block diagram
![Microcontroller based Door lock](https://user-images.githubusercontent.com/98838252/155738896-63c8769b-eabb-4b7d-9cb2-e6147f2f9619.jpg)

## 5 W's and 1H

* What? - gives access to the people you trust (no limit)

* Why? - for the security of our beloved house

* Where? - anywhere the security is needed

* When? - During the time when you are not there to look after the things

* Who? - people who need password secured doors locks

* How? - you can set the password first and then use it to unlock the door
 
## SWOT ANALYSIS
  
  ![secure easy to use](https://user-images.githubusercontent.com/98838252/154832932-4fa8d460-b509-4033-8ea6-4c391959d7f5.jpg)

## Identifying features
   * Screen guides how to enter the password.
   * secure
   * easy to use
   * No crashing happens so that work can be done without any breaks.
## State of art/ Research
    * we need door lock system for securty purposes.


## Requirnments for this project are
    
    * hardware requirnments
        * microcontroller
        * stepper motor
        * keypad
        * buzzer
        * lcd display
        * motor driver controller
        * power source, etc
    
   * HLR and LLR 
    
## High Level Requirements 
|  | High Level Requirements |
|:----|-------------------------|
| HLR1 |	System shall control Door locks by pressing a number on Keypad |
| HLR2 |	There shall be a LCD to display the numbers we press |
| HLR3 |	A password shall be provided for our system |

## Low Level Requirements
|  |Low Level Requirements |
|:----|-------------------------|
| |	Low Level Requirements for HL1	 |
| LLR1.1 |	According to the values of Keypad door locks shall be controlled		 |
| LLR1.2 |	there shall be a sound output for the door lock |	 |
||	Low Level Requirements for HL2 |
|LLR2.1|	Entered value on keypad shall be displayed on LCD Screen|
|LLR2.2 |whether the door is locked or not shall be displayed on screen|
|  |	Low Level Requirements for HL3		|
| LLR3.1|	Device shall open the door lock when the Password is matched		 |
| LLR3.2	|Device shall ask to Re-Enter the Password again if entered one is wrong		 |



        

        
