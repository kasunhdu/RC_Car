# RC_Car
Using two Arduino boards and a nRF24l01 module, I constructed a transmitter and receiver system.
![2023_10_27_22_57_IMG_6194](https://github.com/user-attachments/assets/d5a9b40c-32ce-4cfc-82ad-7fccb399216f)

 I wanted to begin with the fundamentals. In that case, I learnt how to use an Arduino to transmit data using the nRF24L01 module. 
![mini chal orginal 00_00_03_36 Still001](https://github.com/user-attachments/assets/63784d7d-a1e5-498b-8123-9f3564d2b221)

Afterwards, a potentiometer attached to the transmitter was used to control a servo motor and BLDC. 
![mini chal orginal 00_03_03_38 Still004](https://github.com/user-attachments/assets/899b175f-f19e-47eb-8223-0e1f04358bf2)

I then built the transmitter on a PCB using two thumb joystick modules.
![2023_10_25_13_42_IMG_6167](https://github.com/user-attachments/assets/90950201-9922-44b6-ae7f-6730751ec61d)

 The receiver on some vehicle control need to be set. I noticed that car inside my stuff. After that, I removed the car's old 27Mhz receiver system, installed my 2.4Ghz receiver wit a servo to control the steering, and applied the L298N motor driver to move the car forward and backward. Used two 7.4v Li-iron batteries (2*3.7) to power the transmitter and an 11.1v Li-Po battery with 2200mah to the vehicle.
 
![2023_10_27_23_09_IMG_6201](https://github.com/user-attachments/assets/4400bd64-08b9-49a7-a812-969482802f7d)

To supply the servo motor and joystick module 5V power, I used two 7805 regulators (it maintains the Arduino analog readings constant). 
![2023_10_25_13_44_IMG_6168](https://github.com/user-attachments/assets/f2a18831-0bae-46f2-b22e-a53b21b453c6)

Overall, the head and tail lights of the car were fixed making use of a push button on a joystick module.
![mini chal orginal 00_07_30_33 Still012](https://github.com/user-attachments/assets/6570585c-5e7f-4d37-abc9-2f2919b40c0a)
