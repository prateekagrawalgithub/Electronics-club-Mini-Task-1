### Advanced-Rocket-Flight-Computer
Here, I will document on a high-end model **rocket flight computer** for a rocket which can control itself without fins.

**Components used:**
1. Printed Circuit Boards ([downloadable here](https://hacksterio.s3.amazonaws.com/uploads/attachments/1108247/omega_v4_dev_iH8wTGMZul.png))
2. [Teensy 3.5](https://media.digikey.com/pdf/Data%20Sheets/Sparkfun%20PDFs/DEV-14055_Web.pdf)
3. [BMP388](https://www.mouser.com/pdfdocs/BST-BMP388-DS001-01.pdf)
4. [MPU6050](https://www.ti.com/product/DRV8320?HQS=ASC-MDBU-AMD-DRV8320-apc-ds-SFNet-in&DCM=yes&dclid=CILvnMqTlOkCFY9AnQkdp_UEQg)
5. 5050 SMD LED
6. Channel Mosfets

**Basic design:**
* It has 6 axis inertial measurement unit to measure orientation.
* Precise barometer to find the height of flight.
* three pyrotechnic channels to deploy parachutes and light second stage motor.
* communication with LED and buzzer.

**Setup:** PCB is ordered and parts are 3D printed, all soldered and assembled. Arduino IDE and Teensyduino downloaded and codes uploaded.

**Additional comments:** This model eliminates the use of fins in rockets as it can automatically maneuver itself and communicate accordingly. This project serves as a good example of Thrust Vector Control(TVC) and will help eliminate extra load and manual tasks in the control of the rocket.

Full story with 3D print and codes can be found here: [Advanced Rocket Flight Computer](https://www.instructables.com/id/Advanced-Model-Rocket-Flight-Computer/)
