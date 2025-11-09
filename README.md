# PortToPurpose-8051-PIC-Labs
### "I used to skip journaling. Now I document like I debug—precise, relentless, and with style."

---

## Why This Exists

I never cared much for documentation. I believed working code was enough.  
But embedded systems don’t just run—they signal, pulse, and interface with the real world.  
And when the external examiner wants more than just blinking LEDs, you better have proof, process, and presentation.

This repo is my journaled journey through microcontroller practicals—executed on 8051 and PIC18F4520.  
It’s not just code. It’s a portfolio of understanding, a record of resilience, and a tribute to timing.

---

## Microcontrollers Used

- 8051: The classic 8-bit MCU. Timers, ports, and legacy precision.
- PIC18F4520: The modern workhorse. Interrupts, PWM, and serial finesse.

---

## Practicals Covered

### 8051-Based Practicals
1. Flashing LEDs Alternately Using Timer  
   → Delay via Timer 0, Port 0 LED toggling, hex patterns 0xAA and 0x55.

2. Multiplexed 7-Segment Display (0–9)  
   → Segment code lookup, digit enable logic, display refresh.

3. Stepper Motor Interfacing (Software Delay)  
   → Coil energizing sequence, ULN2003 driver, speed control via delay.

4. DAC Interfacing for Sine Wave Generation  
   → Lookup table, waveform synthesis, oscilloscope output.

5. General DAC Interfacing  
   → Static/ramp values, analog output verification.

---

### PIC18F4520-Based Practicals
6. Button, LED, Relay & Buzzer Interfacing  
   → Push-button logic, LCD status display, relay control.

7. LCD Interfacing with PIC  
   → Display “Welcome SIFPU”, 4-bit mode, timing constraints.

8. Square Wave Generation Using Timer with Interrupt  
   → LED toggling, ISR logic, waveform stability.

9. Square Wave Generation Using Timer without Interrupt  
   → Polling-based toggling, delay calibration.

10. Serial Port Interfacing with PC  
    → UART setup, baud rate sync, terminal communication.

11. PWM Signal Generation – Duty Cycles: 80%, 60%  
    → CCP module config, waveform analysis.

12. PWM Signal Generation – Duty Cycles: 40%, 20%  
    → Duty cycle math, oscilloscope verification.

---

## What I Learned

- Microcontroller architecture: SFRs, timers, interrupts, ports.
- Signal generation: Square, sine, triangle, sawtooth.
- Interfacing logic: LEDs, motors, DACs, LCDs, relays.
- Timing mastery: Software vs hardware delay, sampling rate, PWM.
- Documentation discipline: Because working code isn’t enough.

---

## How to Use This Repo

Each folder contains:
- Embedded C code
- Interfacing diagram (conceptual)
- Viva questions and answers
- Calculations (timing, voltage, duty cycle)
- Journal-ready theory notes

---

## Final Thought

"You can’t just blink an LED and call it embedded systems. You have to understand the pulse, the delay, the interrupt, and the waveform. That’s what this repo is about."  
— Me, after surviving the external

---
