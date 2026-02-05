# MYOELECTRIC-ARM
## Myoelectric Arm Control System (MyoArm)

### Problem Statement
Conventional prosthetic and robotic arms often lack intuitive control.
This project focuses on using myoelectric (EMG) signals from human muscles
to control a robotic arm, enabling more natural and responsive motion.

### Objective
- Acquire EMG signals from forearm muscles
- Process and interpret muscle activation patterns
- Control robotic arm movements based on EMG input

### System Overview
The system captures EMG signals using surface electrodes placed on the
forearm. These signals are conditioned, processed, and mapped to specific
arm movements such as gripping or releasing.

### Hardware Components
- EMG sensor module (e.g., MyoWare)
- Microcontroller (Arduino / equivalent)
- Servo motors
- Mechanical arm structure
- Power supply

### Software & Tools
- Embedded C / Arduino IDE
- Signal filtering and thresholding
- Serial communication for debugging

### Methodology
- EMG signals are sampled from muscle contractions
- Noise is reduced using basic filtering techniques
- Signal amplitude is compared against predefined thresholds
- Corresponding motor actions are triggered based on detected muscle activity

### Results
- Successful detection of muscle activation
- Reliable control of basic arm movements such as open and close
- System response observed to be consistent under controlled conditions

### Limitations
- Sensitive to electrode placement and muscle fatigue
- Limited degrees of freedom
- No adaptive or machine-learning-based classification implemented

### Future Improvements
- Multi-gesture recognition using pattern classification
- Improved signal filtering and normalization
- Integration of machine learning for adaptive control
- Enhanced mechanical design for smoother motion

### Artifacts
- Block diagram and system images: media/
- Test results and observations: results/
- Detailed project report: docs/

### My Role
- System design and integration
- EMG signal acquisition and processing
- Embedded programming and testing
- Documentation and result analysis
