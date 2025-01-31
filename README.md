# Robotic-Arm-Calculations

🦾 Torque Calculation and Servo Motor Selection for Robotic Arm




# The task 

Calculate the required torque for each motor in the robotic arm and find a suitable servo motor for each joint

![Image](https://github.com/user-attachments/assets/0747f5a5-15c1-4e7f-ad17-6754e8d49e2a)







# 📌 Given Data

- Mass of the object: 1 kg
- Length of the first arm: 10 cm = 0.1 m
- of the second arm: 15 cm = 0.15 m
- Distance from the motor to the center of mass: 4 cm = 0.04 m
- Acceleration due to gravity: 9.81 m/s²



# ⚙️ 1. Calculating the Force

To calculate the force due to weight:
Force = mass × g

---> g is the acceleration due to gravity (9.81 m/s^2):
Force = 1 kg × 9.81 m/s^2 = 9.81 N




#  2. Calculating the Torque for Each Motor

Torque is calculated using the formula:

Torque = Force × Distance


a. Torque at the first motor:
The distance from the first motor to the center of mass is the length of the first arm (10 cm or 0.1 m): Torque(1) = 9.81 N × 0.1 m = 0.981 N\cdotpm


b. Torque at the second motor ---> Using the Distance to the Center of Mass: 
The distance from the second motor to the center of mass is the sum of the lengths of both arms (10 cm + 15 cm = 25 cm or 0.25 m):
Torque(2) = 9.81 N × 0.25 m = 2.4525 N\cdotpm

When Using the Distance from the Motor to the Point of Force Application:
If you use the distance from the second motor to the point of force application (which is 15 cm):
Torque(2) = 9.81 N × 0.15 m = 1.4715 N\cdotpm




# Results

First motor: Requires at least 0.981 N·m of torque

Second motor: Requires at least 2.4525 N·m of torque




# 🛒 Where to Buy Servo Motors

ElectroCraft: [Visit Website](https://www.electrocraft.com/)

Amazon: [Visit Website](https://www.amazon.com/)

RobotShop: [Visit Website](https://www.robotshop.com/)
