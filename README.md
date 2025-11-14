**🔢 Seven Segment Display Countdown – Arduino Project**

This project demonstrates how to display digits 0 to 9 on a 7-segment display using an Arduino by manually controlling each segment (a–g).
Each number is displayed for 1 second, and the pattern repeats continuously.

This is a great beginner project to understand how seven-segment displays work and how to control individual segments using digital pins.


**👨‍💻 Author**

Name: Rohit Gupta

Project: Seven Segment Countdown – Arduino Project


**✨ Project Overview**

1. Uses seven Arduino digital pins (1–7) to represent the seven segments of a common-cathode or common-anode 7-segment display.

2. Displays digits from 0 → 9 sequentially.

3. Each digit is shown for 1000 ms (1 sec).

4. Helps understand segment control logic and timing in embedded systems.


**🔧 Hardware Requirements**

1. Arduino UNO / Nano / Mega

2. Seven-segment display (common cathode recommended)

3. 7 × 220Ω resistors (one for each segment)

4. Jumper wires

5. Breadboard


**▶️ How to Use**

1. Connect Arduino pins 1–7 to the corresponding segment pins of the display.

2. Connect common pin to:

      a. GND (for common cathode)
      
      b. 5V (for common anode)

3. Open the .ino file in Arduino IDE.

4. Select the board and port.

5. Upload the sketch.

6. Watch numbers 0 → 9 appear one after another every second.


<img width="1182" height="688" alt="image" src="https://github.com/user-attachments/assets/922c79ea-e2ff-419a-8c68-8732e1762531" />


<img width="1218" height="830" alt="image" src="https://github.com/user-attachments/assets/b790fded-ddd4-475d-9983-a0425ce30035" />



**🎯 Learning Outcomes**

1. Understanding 7-segment display architecture

2. Mapping segment logic for digits

3. Controlling multiple outputs with Arduino

4. Using digitalWrite() and delay()

5. Basics of hardware interfacing
