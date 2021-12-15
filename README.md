# Industrial-Automation-PLC---ICT4---Conveyor-Sorting-System-w--HMI

- Implemented conveyor sorting and assembly system with HMI for remote control and monitoring. 
- Used PID controller tuned via Zeighler Nichols to regulate the Oven temperature to a desired setpoint
- Tested on physical Bytronic Kit while mostly designed using Simumatik (Digital Twin) 

- Siemens TIA Portal - PLC - Bytronic Kit - HMI - PID Controller - Simumatik (Digital Twin) 

# Discription   
The ICT4 is a representation of a typical industrial automation system and includes component sorting, assembly, inspection and accept/reject processes. The ICT4 can be connected to a PC through a USB connection or to a PLC using the 24V D connectors. The system has been designed to realistically represent a component sorting, assembly and inspection process that can be controlled from a PC and virtually any PLC that is commonly available. The ICT4 consists of a chain conveyor and belt conveyor that are fitted with a variety of industrial sensors and 24V d.c. actuators. In principle, the ICT4 is designed to sort an aluminium peg from a plastic ring, assemble the ring on top of the peg and then determine whether they have been correctly assembled before either accepting or rejecting the part. The components are initially randomly placed on the chain conveyor which lifts them to a higher level. When the higher level is reached, the plastic components are detected by an infra-red sensor and ejected by a solenoid down an assembly chute. The aluminium pegs continue on the conveyor and are deflected down the feeder chute. From the feeder chute the aluminium components are automatically fed on to the belt conveyor. An infra-red sensor is used to determine if the plastic ring ‘hopper’ is empty, or not. If it is empty, a rotary solenoid is used to dispense a ring from the assembly chute into the hopper. The hopper is positioned just above the belt conveyor and, when the aluminium peg passes, the peg engages with the hole in the ring and the two are assembled. Inductive, capacitive infra-red and fibre optic industrial sensors positioned along the belt conveyor are used to check for correct assembly. Components that have not been assembled are ejected by a solenoid into a ‘scrap’ or ‘recycle’ bin, correctly assembled components pass into a finished parts tray.

# Screenshots 
## HMI 

![image](https://user-images.githubusercontent.com/42310216/146128267-f4543fa7-d1ea-4220-bd41-74967586e9d5.png)


## In Action 

![Working screenshots](https://user-images.githubusercontent.com/42310216/146128308-b1a1e105-8966-46fd-8b58-6b32c1e17778.PNG)


## Temperature/Control Consideration 

![plc](https://user-images.githubusercontent.com/42310216/146128367-2e26adb7-d554-43be-af2d-2f85b36ddac1.PNG)
