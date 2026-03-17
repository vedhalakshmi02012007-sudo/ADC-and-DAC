
## Experiment 7(b): Digital to Analog Converter (DAC) using Proteus
## Aim
To design and simulate a Digital to Analog Converter (DAC) circuit using Proteus and observe the conversion of digital signals into analog output voltage.
## Apparatus / Software Required
•	Proteus Design Suite
•	DAC IC (DAC0808)
•	Resistors
•	Operational Amplifier (e.g., µA741)
•	Digital input switches
•	Power supply
## Theory
A Digital to Analog Converter (DAC) converts digital binary data into an equivalent analog voltage or current.
The DAC0808 is an 8-bit DAC that produces an analog current proportional to the digital input. An operational amplifier is used to convert the output current into a voltage signal.
Features
•	8-bit resolution
•	Fast conversion
•	Compatible with digital systems
The analog output voltage depends on the digital input combination.
## Circuit Diagram

<img width="1920" height="1140" alt="Screenshot 2026-03-10 142219" src="https://github.com/user-attachments/assets/d0490a6f-b7b9-456e-8b51-517c6d12c899" />

Design the circuit in Proteus using DAC0808 with:
•	8 digital switches for binary input
•	Op-Amp for current to voltage conversion
•	Output connected to voltmeter
## Procedure
1.	Open Proteus software.
2.	Select components:
o	DAC0808
o	Operational amplifier (741)
o	Resistors
o	Digital switches
3.	Connect binary inputs (D0–D7) using switches.
4.	Connect DAC output to the op-amp circuit.
5.	Connect a voltmeter at the output.
6.	Run the simulation.
7.	Change digital input combinations and observe the output voltage.

## Tabulation

| S.No | D | C | B | A | Binary Input (DCBA) | Output Voltage (V) |
|------|---|---|---|---|----------------------|-------------------|
| 1    | 0 | 0 | 0 | 0 | 0000                 | -0.25            |
| 2    | 0 | 0 | 0 | 1 | 0001                 | -0.30            |
| 3    | 0 | 0 | 1 | 0 | 0010                 | -0.38            |
| 4    | 0 | 0 | 1 | 1 | 0011                 | -0.50            |
| 5    | 0 | 1 | 0 | 0 | 0100                 | -0.55            |
| 6    | 0 | 1 | 0 | 1 | 0101                 | -0.63            |
| 7    | 0 | 1 | 1 | 0 | 0110                 | -0.68            |
| 8    | 0 | 1 | 1 | 1 | 0111                 | -0.75            |
| 9    | 1 | 0 | 0 | 0 | 1000                 | -0.80            |
| 10   | 1 | 0 | 0 | 1 | 1001                 | -1.43            |
| 11   | 1 | 0 | 1 | 0 | 1010                 | -0.63            |
| 12   | 1 | 0 | 1 | 1 | 1011                 | -0.68            |
| 13   | 1 | 1 | 0 | 0 | 1100                 | -0.75            |
| 14   | 1 | 1 | 0 | 1 | 1101                 | -0.80            |
| 15   | 1 | 1 | 1 | 0 | 1110                 | -0.38            |
| 16   | 1 | 1 | 1 | 1 | 1111                 | -0.25            |

## Result
The Digital to Analog Converter circuit was successfully designed and simulated in Proteus, and the digital input was converted into corresponding analog voltage.

## Applications of ADC and DAC
•	Data acquisition systems
•	Digital signal processing
•	Microcontroller interfacing
•	Audio and video processing
•	Instrumentation systems
