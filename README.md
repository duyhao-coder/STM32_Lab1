                                               LAB1: STM32 PROJECT
I/Exercise_1
From the simulation on Proteus, one more LED is connected to pin PA6 of the STM32 (negative pin of the LED
is connected to PA6). The component suggested in this exercise is LED-YELLOW, which can be found from the 
device list. 
In this exercise, the status of two LEDs are switched every 2 seconds, as demonstrated in the
figure bellow.
![image](https://github.com/user-attachments/assets/449201da-273f-4986-ba8b-a576e143e165)
II/Exercise_2
Extend the first exercise to simulate the behavior of a traffic light. A third LED, named LED-GREEN is added
to the system, which is connected to PA7. A cycle in this traffic light is 5 seconds for the RED, 2 seconds
for the YELLOW and 3 seconds for the GREEN. The LED-GREEN is also controlled by its negative pin.
![image](https://github.com/user-attachments/assets/54297d71-cdba-4a88-b218-616e87c77a80)
III/Exercise_3
Extend to the 4-way traffic light. Arrange 12 LEDs in a nice shape to simulate the behaviors of a traffic light.
A reference design can be found in the figure bellow.
![image](https://github.com/user-attachments/assets/f5cf0cca-6f19-4c10-a760-e76f7d6c28f2)
IV/Exercise_4
Add only one 7 led segment to the schematic in Exercise 3. This component can be found in Proteus by the keyword
7SEG-COM-ANODE. For this device, the common pin should be connected to the power supply and other pins are supposed
to connected to PB0 to PB6. Therefore, to turn-on a segment in this 7SEG, the STM32 pin should be in logic 0 (0V).

Implement a function named display7SEG(int num). The input for this function is from 0 to 9 and the outputs are 
listed as following
![image](https://github.com/user-attachments/assets/996b3441-dc49-48fc-be68-d7f51405f320)
V/Exercise_5
Integrate the 7SEG-LED to the 4 way traffic light. In this case, the 7SEG-LED is used to display countdown value.
In this exercise, only source code is required to present. The function display7SEG in previous exercise can be re-used.
![image](https://github.com/user-attachments/assets/f1181921-48e8-48a0-bbad-9bbe7968e1ae)
VI/Exercise_6
In this exercise, a new Proteus schematic is designed to simulate an analog clock, with 12 different number. The
connections for 12 LEDs are supposed from PA4 to PA15 of the STM32. The arrangement of 12 LEDs is depicted as follows.
![image](https://github.com/user-attachments/assets/7b977735-d309-48cb-8282-7e274b137256)
X/Exercise_10
Integrate the whole system and use 12 LEDs to display a clock. At a given time, there are only 3 LEDs are turn on for
hour, minute and second information.
![image](https://github.com/user-attachments/assets/8d5556fa-f637-4d36-bcec-e1506d8f0081)









