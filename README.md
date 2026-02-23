Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
<img width="1920" height="1200" alt="Screenshot 2026-02-23 092202" src="https://github.com/user-attachments/assets/c70ebda0-87ee-453d-9f2b-9b1f5b07fbc9" />

## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1384" height="883" alt="image" src="https://github.com/user-attachments/assets/d5d31719-3b7a-4725-9717-982f5251857a" />

## Tabulation
S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)

| S.No | Vin (V) | Theoretical Gain | Theoretical Vout (V) | Practical Vout (V) |
| ---- | ------- | ---------------- | -------------------- | ------------------ |
| 1    | 0.1     | 11               | 1.1                  | 1.08               |
| 2    | 0.2     | 11               | 2.2                  | 2.16               |
| 3    | 0.3     | 11               | 3.3                  | 3.26               |
| 4    | 0.4     | 11               | 4.4                  | 4.34               |
| 5    | 0.5     | 11               | 5.5                  | 5.40               |

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions

1.	What is a Non-Inverting Amplifier?
	A non-inverting amplifier is an op-amp circuit where input is applied to the positive (+) terminal.
The output is amplified and remains in the same phase as the input.

2.	What is the gain formula?
  The gain of a non-inverting amplifier is Av = 1 + (Rf / R1).
Rf is feedback resistor and R1 is resistor connected to ground.

3.	Why is output in phase?
	Because the input is given to the non-inverting (+) terminal of the op-amp.
So the output signal has the same phase as the input signal.

4.	What happens if Rf increases?
 	If feedback resistance Rf increases, the gain increases.
So the output voltage also increases.

5.	What is the input impedance of non-inverting amplifier?

The input impedance is very high in a non-inverting amplifier.
It draws very little current from the input source.

