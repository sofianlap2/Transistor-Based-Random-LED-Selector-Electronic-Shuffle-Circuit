# Transistor-Based-Random-LED-Selector-Electronic-Shuffle-Circuit
Transistor-Based Random LED Selector (Electronic Shuffle Circuit)

This project is a random LED selector circuit built using discrete components and two 2N4401 NPN transistors in a bistable multivibrator configuration.

When the push button (SW1) is pressed, the circuit becomes unstable for a short time due to the charging and discharging of capacitors (C1 and C2). During this moment, the two transistors compete to turn ON first. Because of small component tolerances and capacitor timing differences, one transistor wins randomly, turning ON its corresponding LED while the other remains OFF.

Once the button is released, the circuit latches into a stable state, keeping only one LED ON — effectively acting as a simple electronic shuffle or winner selector.
--Main Components:
•	2 × 2N4401 NPN Transistors
•	2 × 10µF Capacitors (timing elements)
•	10kΩ resistors (biasing and feedback network)
•	1kΩ resistors (LED current limiting)
•	2 LEDs
•	9V Battery
•	Push button switch
--What I Learned:
•	Designing and analyzing a bistable multivibrator
•	Transistor biasing and saturation behavior
•	RC timing circuits and capacitor charging/discharging
•	Positive feedback and latching circuits
•	Practical troubleshooting between simulation and real hardware

<img width="1090" height="840" alt="image" src="https://github.com/user-attachments/assets/e6eb0a1d-d802-4629-beff-a4eda832cc0d" />
<img width="698" height="394" alt="image" src="https://github.com/user-attachments/assets/32304cc8-303e-4b2e-b8a4-6ab1aecc83ea" />
