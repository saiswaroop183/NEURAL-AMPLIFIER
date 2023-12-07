# NEURAL-AMPLIFIER
low noise low power nueral amplifier with OTA topology
                                                                       **Analog IC Design : Course Project
                                                          Monsoon 2022, IIIT Hyderabad (Instructor: Prof. Abhishek Srivastava)
                                                                     Due date : 20 Nov, 2022 (18:00 hrs)**
**Instructions:**
1. Submit your project report in form of pdf (Name RollNo.pdf) at moodle on or before the due date
2. Use the given SCL 180 nm technology file for the simulations.
3. Design the circuit for VDD ≤ 1.8 V.
1 Design specifications
Design the low noise low power neural amplifier (Fig. 1 in the paper) using the OTA topology
(Fig. 4 in the paper) given in the following research paper:
R. R. Harrison and C. Charles, A low-power low-noise CMOS amplifier for neural recording
applications, IEEE J. Solid-State Circuits, vol. 38, no. 6, pp. 958965, Jun. 2003.
Design for the following specifications :
• DC gain ≥ 60dB.
• -3 dB bandwidth ≥ 10 kHz.
• Input referred noise ≤ 2 µ Vrms.
• CMRR ≥ 100 dB.
• Noise efficiency factor (NEF) ≤ 4
• DC power consumption ≤ 30 µA
• Supply voltage ≤ 1.8 V
**2 Hand calculations**
(a) Clearly draw the OTA schematic (Fig. 4 in the paper) using xcircuit or some other drawing
software and label the transistors, resistors and capacitors. [5]
(b) Show the step-by-step procedure and calculations for OTA design. [10]
(c) Tabulate the design parameters (W, L, R, C, I). [5]
(d) Tabulate the calculated specifications (gain, unity gain bandwidth, slew rate, phase margin) for the OTA. [5]
3 OTA Simulations
(a) Use LTSPICE and SCL 180 nm model file and report the drawn circuit with chosen MOSFETs. [10]
(b) Tabulate the design parameters (W, L, R, C, I etc) and compare with the hand calculate
values. [5]
**(c) OPERATING POINT [5]**
Perform the dc operating point analysis with the OTA. Clearly annotate and report the dc
operating point voltages at every node on the schematic. Ensure that your circuit is biased
as desired.
**(d) STB ANALYSIS: [5]**
report the DC gain, unity gain frequency and the phase margin. Also show the magnitude
and phase plot.
**(e) SLEW RATE: [5]**
With the OTA in unity gain feedback mode, apply a positive step from 0 to 1.8V with a
rise time of 100 ps. Measure the slew rate and clearly show the output plot in the slewing
region with cursors.
**(f) SETTLING TIME: [5]**
With the OTA in unity gain feedback mode, apply the same step input as above. Measure
and report the settling time, ts for 2% accuracy.
**(g) SYSTEMATIC OFFSET: [5]**
With the OTA in unity gain feedback mode, measure and report the systematic offset value
using dc analysis. Clearly show the output node voltage on the schematic.
**(h) NOISE: [5]**
Show the input referred noise PSD from 1Hz to 1GHz band. Clearly show the RMS
thermal noise voltage in the plot (with cursor). Report the integrated noise voltage over
the unity gain bandwidth.
**(i) CMRR: [5]**
Plot the open loop CM gain of the OTA with clear labels. Report the CMRR of the OTA.
**(j) PSRR: [5]**
Perform the PSRR simulation by adding a small signal component only on the voltage
supply of the OTA. Plot and report the PSRR value with clear labels (Open loop).
**(k) INPUT COMMON MODE RANGE:**
 Sweep the input common mode voltage in the unity
gain configuration and report the maximum input common mode range of the OTA. [5]
**(l) CLOSED LOOP GAIN:******
With the OTA in unity gain feedback mode, perform ac analysis
and report the DC gain and the -3dB frequency. [5]
**(m) CLOSED LOOP TRANSIENT ANALYSIS: [5]**
With the OTA in unity gain feedback mode, apply a sinusoidal signal of 10KHz frequency
for maximum signal swing at the output without distortion.
**(n) POWER CONSUMPTION: [5]**
Report the total current and power consumption of the OTA.
**4 Pseudo resistor design [20]**
Design the pseudo PMOS resistor shown in the Fig. 1 in the paper. Simulate and plot its I-V
characteristics and incremental resistance vs incremental voltage across it.
**5 Neural amplifier design [30]**
Use the OTA and and pseudo resistor to build the neural amplifier (Fig. 1 in the paper). Report
capacitor values (C1, C2), sizing for pseudo PMOS resistor. Run necessary simulations (DC,
AC, transient, noise, CMRR, PSRR etc) and report the achieved specifications
6 Tabulating the results [10]
From the schematic simulations, tabulate the OTA and neural amplifier performance (DC gain,
unity gain frequency, phase margin, ICMR, CMRR, PSRR, slew rate, output swing (peak
to peak), RMS thermal noise, power) and compare with the required specifications. (Table
columns - specifications — Schematic)
7 Project report [20]
Project report must be concise and systematic. Professional write up is expected. The best
report will be awarded bonus (10) marks. The best executed project will be given a prize and
will be announced on the moodle.
8 Project viva [20]
It will be held on 3
rd Dec, 2022. Timings will be intimated later.
2
