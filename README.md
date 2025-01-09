# Digital-Clock
A functional HH:MM:SS digital clock using a PIC16F877A microcontroller.

### Schematic Diagram
![image](https://github.com/user-attachments/assets/04fe3363-24d0-4a38-b9b5-0a17704dc37d)

### Breadboard Implementation
![image](https://github.com/user-attachments/assets/7ba5f41b-21f0-42b7-8465-7abeb9de17a3)

### Results
The project is divided into three main parts based on the functionality of the circuit: the Digital
Clock, Stopwatch and Countdown Timer. Beginning with the digital clock, it was successfully
implemented on the PIC microcontroller using the four 7-segment displays. The clock supports both
24-hour and 12-hour formatting and is selectable via a button trigger. The circuit also accurately
displays the current time with minimal to no deviation between second delays. Testing the circuit
manually also revealed smooth transitions between the two different time formats.

![image](https://github.com/user-attachments/assets/06ae342d-dae8-41bc-8df3-dfa41e72b87b)

Moving to the second function of the circuit, the stopwatch feature was seamlessly integrated into
the clock circuit. It operates with three separate buttons functioning as start, pause and reset in order to
operate the stopwatch. Manually testing the circuit proved that the implemented code was successful in
having a precise timing as well as very minimal drifting due to unsynced delays.

![image](https://github.com/user-attachments/assets/ebd96937-9603-45fc-9d44-9cb06a734bae)

The final implementation done was a countdown timer which was incorporated into the main
digital clock structure. The user is able to set a desired countdown value and has the timer begin to
count to zero beginning from that value. Similar to the prior integrations, the testing confirmed an
accurate countdown and reliable performance when handling long-duration countdowns.
The successful implementation of the digital clock shows the flexibility and efficiency of the PIC
microcontroller when handling a circuit with varying purposes. The modular approach taken in
designing each component also aided in the easy integration of the different functions.
