# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
<img width="1600" height="1098" alt="image" src="https://github.com/user-attachments/assets/893c6091-0d39-40b1-8310-43598f7d49ac" />




---

## MODEL GRAPH
<img width="1600" height="557" alt="image" src="https://github.com/user-attachments/assets/0c0586ef-1052-4683-8bbc-c413d4677908" />


## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION


| S.No | Amplitude (Volts) | Time Period (ms) | Frequency (Hz) |
|------|--------------------|------------------|----------------|
| 1    |   12.0                 |     5.17             |       193.6         |

---
## OUT PUT WAVEFORM AND DISCUSSION 

![IMG-20251204-WA0020 1](https://github.com/user-attachments/assets/52e2abcd-9795-4673-a295-3a727fce417e)

---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2025-11-27 at 22 01 49](https://github.com/user-attachments/assets/5f86abd1-e548-4b6d-9c42-123af259a6a9)



---
## MODEL GRAPH
![WhatsApp Image 2025-11-27 at 22 02 02](https://github.com/user-attachments/assets/4152d80b-88ca-4536-b891-98ed69533cdf)


---

## DESIGN

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION


| S.No | Amplitude (Volts) | Time Period (ms) | Frequency (Hz) |
|------|--------------------|------------------|----------------|
| 1    |   21                 |     0.72             |     1.37           |

---
## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251204-WA0020 1](https://github.com/user-attachments/assets/6c092189-33d7-48ad-bead-44c608750864)


---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
