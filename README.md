# led-chaser-
chaser circuit using ic
LED Chaser Circuit Using IC

A simple LED chaser (running light) circuit that sequentially lights up LEDs in a pattern. It uses a 555 timer IC to generate clock pulses and a 4017 decade counter IC to control the LEDs. This project is ideal for learning about timers, counters, and sequential logic in electronics.

Components Needed

IC 555 Timer

IC 4017 Decade Counter

LEDs (5–10 depending on design)

Resistors (220–470 Ω for LEDs)

Capacitor (e.g., 10 µF for 555 timing)

Breadboard & jumper wires

Power supply (5V–12V depending on IC)

Working Principle

555 Timer operates in astable mode to generate continuous clock pulses.

4017 Decade Counter receives pulses from the 555 timer and sequentially activates its 10 output pins.

Each output pin is connected to an LED through a current-limiting resistor.

LEDs light up one by one in sequence, creating the "running light" effect.

The speed of the sequence can be adjusted by changing the resistor and capacitor values on the 555 timer.

Circuit Notes

The reset pin of 4017 can be connected to any output to control the number of LEDs in the sequence.

Ensure correct LED polarity (long leg → anode).

Adjust R and C in 555 timer to modify blinking speed.
