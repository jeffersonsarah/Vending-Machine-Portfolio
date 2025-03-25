# Vending-Machine-Portfolio

# SR Latch
There are two inputs for the SR Latch: S for set and R for reset, and Q the output. When S = 1, Q = 1. When S = 0, Q = 1, that is because the latch remembers the last input. So then when R = 1, Q = 0 and it resets. 
![image](https://github.com/user-attachments/assets/eebb2cae-5fb6-4305-abdc-501845d4d12d)

# Circuit Diagram
![image](https://github.com/user-attachments/assets/0f6c2db1-b23b-41c8-a971-b93fdf443f35)

![image](https://github.com/user-attachments/assets/229aadf2-be46-45ea-a454-176584f2bfd9)

# How it works
Coin Input
![image](https://github.com/user-attachments/assets/6d7b3edd-21f1-4fcd-89f7-9d3bdfb3b50a)
In this picture you press the switch making the circuit realize that a coin has been entered into the vending machine. 

Item Selection
![image](https://github.com/user-attachments/assets/d426108c-1491-4b92-ae88-e92aa3087a55)
In this picture the user presses another switch signaling to the vending machine that an item has been selected. 

Delayed Reset
![image](https://github.com/user-attachments/assets/e7c71281-b210-4025-a97d-d928519e2a4b)
In this picture the capacitor starts to charge and the reset is delayed a bit. 

Final reset and ready for next purchase
![image](https://github.com/user-attachments/assets/f2b8b22e-77f3-44f5-b059-f86dbbae9741)
In this picture the ciruit is fully reset and ready for another coin to ender the vending machine and another selection process.

# Old School Vending Machine
![image](https://github.com/user-attachments/assets/5a3a40cc-8593-4162-8c84-8085f69325f7)

Our circuit is a simplified version of this old vending machine because we only have one option to pick whereas for this vending machine there are multiple options and outcomes to get from the vending machine.

# Raspberry Pi Vending Machine

A Raspberry Pi is a very small computer that makes physical compputing and electronics a lot easier. You are able to code through the Raspberry Pi so that you don't have to mess with multiple resistors, copasitors, led lights, and wires. 

# Pocess of creating vending machine
![image](https://github.com/user-attachments/assets/8a20a18e-0db3-438d-9925-0791e5f6e44c)

![image](https://github.com/user-attachments/assets/7f44c17b-c9cd-4b72-b10b-243699ea0e74)

In this picture, we are putting together the breadboard which basically works as the visualization for what we code to the Raspberry Pi. 

![image](https://github.com/user-attachments/assets/75bc943a-d5db-41cf-93fb-711cda288100)

This is how the breadboard is created. There are two switches that simulate the coin going into the machine and the coin vending into the machine. The led light shows that the coin is being used to get a product out of the vending machine. 

![image](https://github.com/user-attachments/assets/5cea6cd3-9e43-4501-88b7-ec4f5d624a25)

In this portion of code it creates the simulation of pressing the first button to make the coin count go up by one each time you press the button. Then when you press the second button is subtracts one from the coin count and lights up the led for a short amount of time.
![image](https://github.com/user-attachments/assets/125d8cbc-3542-4237-97ed-5746273f643e)

This is when you press the button and the coin count goes up.

![image](https://github.com/user-attachments/assets/eb89f902-6840-4b33-b222-6b9a835913f1)

This is when you press the vending button and the light temporarily turns on.

![image](https://github.com/user-attachments/assets/ef9bea04-a228-4e96-8fa9-08a6f337e060)

This portion of the code created a html file that you can use the IP Adress for the Raspberry Pi to locate and look at the html page. On the page it updates the number when you press the coin button and updates the number when the vending number is pressed.

# Work Cited
Justice, M. (2020). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine. No Starch Press.
