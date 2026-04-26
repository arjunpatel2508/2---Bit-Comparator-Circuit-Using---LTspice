# 2---Bit-Comparator-Circuit-Using---LTspice

DESCRIPTION 


The design was implemented using fundamental logic gates such as AND, OR, and NOT, constructed within the LTspice environment. Each comparison condition was derived using Boolean logic expressions and verified through simulation waveforms.


*COMPONENTS REQUIRED TO OPERATE OR PERFOM 2 BIT COMPARATOR.* 

1. Input Sources
4 Voltage Sources (Pulse Inputs):
V1
V2
V3
V4
These generate the binary inputs for A1, A0, B1, B0.

2. Logic Gates
From the labels (A4–A15), the circuit is built using:

AND Gates:
Used to implement comparison conditions
→ Approx: 6 gates (A4, A6, A7, A12, A13, A14)
OR Gates:
Used to combine logic conditions
→ Approx: 3 gates (A5, A8, A15)
XNOR Gates (for equality check):
→ Approx: 2 gates (A9, A10)
AND Gate (final equality output):
→ 1 gate (A11)

3. Wiring & Nodes
Interconnections (wires)
Junction nodes (for signal branching)

4. Outputs
A < B
A = B
A > B

Final Component Count (Summary)
Voltage Sources: 4
Logic Gates: ~12 total
AND: ~7
OR: ~3
XNOR: ~2


1. CONNECTION FOR 2 BIT COMPARATOR IN LTspice 

<img width="935" height="524" alt="Screenshot 2026-04-26 170123" src="https://github.com/user-attachments/assets/bbf8ef21-5b3f-4493-95d7-8bfaa8f6cfca" />

2. CORRESPONDING OUTPUTS OF 2 BIT COMPARATOR CIRCUIT

   <img width="1129" height="650" alt="Screenshot 2026-04-26 170251" src="https://github.com/user-attachments/assets/f9ac7f4a-16a5-4705-ac0e-75cf50924147" />
