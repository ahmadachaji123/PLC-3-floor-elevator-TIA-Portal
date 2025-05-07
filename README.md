This project demonstrates a fully automated 3-floor elevator system developed using the Siemens S7-1500 PLC and a custom HMI interface. The system simulates realistic elevator behavior and is designed for learning and testing core industrial automation concepts.

🔧 Key Features:
Sensor-Based Floor Detection: Each floor is equipped with sensors to track the elevator's position.

Fail-Safe Routine: If the elevator fails to detect any floor sensor after a button press, it checks the door status, closes it if open, and moves downward until it reaches a floor.

HMI Integration: Allows users to control the elevator, monitor input/output status, and view alarms. Includes ring and stop buttons, floor call buttons, and manual overrides.

Floor Call & Prioritization: Handles multiple simultaneous button presses with logic prioritizing higher floor requests.

Door Logic with Safety Sensors:

Door closes only after sensor confirmation.

If the safety sensor is triggered during closing, the door remains open until safe.

Stop & Start Functionality: A stop button halts all outputs, while the start button resumes operations without system reset.

Alarms and Diagnostics: Alarms (with audio cues) notify users of faults or errors, all resettable via HMI.

Visual Feedback: All system states, sensor inputs, and actuator outputs are clearly shown on the HMI for real-time understanding.

🎥 Note: Audio explanations have been added using CapCut to enhance clarity during the demonstration.

This project is ideal for those exploring PLC control logic, HMI development, and industrial-grade safety implementations in elevator automation.
