# Quadcopter Drone with KK2.1.5

## Introduction
This project demonstrates a quadcopter drone built using the KK2.1.5 flight controller, ESCs, motors, and a custom frame. The drone is designed for beginners in drone development and DIY enthusiasts.

## Features
- Flight Controller: KK2.1.5
- Motors: 1000kv brushless motor
- ESCs: ESC 30A simonK
- Frame: F450 Frame
- Transmitter: Turnigy 9X 9Ch Mode 2
- Receiver: iA8 Receiver (AFHDS 2A system)


## Components
1. 1x KK2.1.5 Flight Controller
2. 4x ECS 30A simonK 
3. 4x 1000kv brushless motors
4. 1x F450 Drone Frame
5. 4x 10*4.5 inch Propellers
6. 1x Turnigy 9X 9Ch Mode 2
7. 1x iA8 Receiver (AFHDS 2A system)

## Assembly
1. Frame Setup:
   - Assemble the F450 frame by attaching the arms to the main body.
   - Securely mount the motor mounts at the end of each arm.
2. Motor Installation:
   - Attach one motor to each arm of the frame.
   - Ensure that two motors are clockwise (CW) and two are counterclockwise (CCW) to balance the thrust.
3. ESC Wiring:
   - Connect each motor to an ESC using the three motor wires.
   - Ensure the phase wires are connected correctly; adjust them later if the motor spins in the wrong direction it will tell you the direction of the motors in the      flight controller screen.
4. Flight Controller Placement:
   - Place the KK2.1.5 flight controller at the center of the F450 frame.
   - Secure it with double-sided tape or screws becarful of the frame because it has conductive material so the KK2.1.5 don't get shorted, ensuring it's level and 
     oriented correctly (front marked on the controller matches the frame's forward direction).
5. ESC to Flight Controller:
   - Connect the ESC signal wires to the corresponding motor channels on the KK2.1.5.
    For a quadcopter:
    Motor 1 (front-left): Channel 1.
    Motor 2 (front-right): Channel 2.
    Motor 3 (rear-right): Channel 3.
    Motor 4 (rear-left): Channel 4.
6. Receiver Connection:
  - Plug the receiver wires into the KK2.1.5 flight controller, matching the channels to your transmitter configuration (Throttle, Roll, Pitch, Yaw).
7. Power Distribution:
   - The F450 frame includes an integrated Power Distribution Board (PDB) in its lower plate. This simplifies the process of connecting and distributing power to         all components in the quadcopter. Here's how the power distribution is managed:

  Battery Connection:
  The LiPo battery connects to the PDB using an XT60 connector. This provides the main power source for the drone.
  ESC Connections:
  - Each Electronic Speed Controller (ESC) is directly soldered to the PDB. The positive (red) and negative (black) wires from each ESC are connected to the     
    designated pads on the board. This distributes power evenly to all motors.
  Switch (Optional):
  - A switch can be added between the battery and the PDB for easier power control during assembly and testing.
    This integrated PDB design keeps the wiring organized, reduces weight, and ensures efficient power distribution to all components of the drone.
8. Propeller Attachment
  - Attach the propellers to the motors after confirming the motor direction.
    Ensure CW and CCW propellers are correctly placed to generate lift.
9. Battery Connection
  - Connect the battery to the power distribution system through the breadboard and switch.
    Use a LiPo alarm or voltage checker to avoid over-discharging.
10. Calibration and Testing
 - Calibrate the ESCs by following the KK2.1.5 calibration procedure.
   Test the transmitter-receiver pairing.
   Use the KK2.1.5 interface to configure and tune the flight parameters (e.g., PIDs).


## Future Enhancements
- Add a camera for FPV.
- adding a gimbal for the camera.
- Integrate GPS for waypoint navigation.
- Improve battery efficiency.


