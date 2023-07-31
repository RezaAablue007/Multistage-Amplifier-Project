# Multistage Amplifier Project

## Introduction
This report presents the Amplifier Design Project conducted on April 1, 2021. The objective of the project was to design a BJT (Bipolar Junction Transistor) amplifier according to the specified requirements outlined in the project manual.

## Objectives
The main specifications and objectives for the amplifier design were as follows:
- Power supply: +10V relative to ground.
- Total quiescent current drawn from the power supply: Not greater than 10 mA.
- No-load voltage gain (at 1 kHz): |Av0| = 50 (±10%).
- Maximum no-load output voltage swing (at 1 kHz): Not smaller than 8 V peak-to-peak.
- Loaded voltage gain (at 1 kHz and with RL = 1 kΩ): Not smaller than 90% of the no-load voltage gain.
- Maximum loaded output voltage swing (at 1 kHz and RL = 1 kΩ): Not smaller than 4 V peak-to-peak.
- Input resistance (at 1 kHz): Not smaller than 20 kΩ.
- Amplifier type: Inverting or non-inverting.
- Frequency response: 20 Hz to 50 kHz (-3dB response).
- Type of transistors: BJT.
- Number of transistors (stages): Not more than 3.
- Permitted resistances: Values smaller than 220 kΩ from the E24 series.
- Permitted capacitors: 0.1 μF, 1.0 μF, 2.2 μF, 4.7 μF, 10 μF, 47 μF, 100 μF, 220 μF.
- Other components (BJTs, diodes, Zener diodes, etc.): Only from the ELE404 lab kit.

## Description of Amplifiers
For the project, two types of amplifiers are used to construct the multistage amplifier: the Common Collector (CC) and the Common Emitter (CE) amplifiers. Each amplifier has distinct characteristics in terms of voltage gain, input resistance, output resistance, and modes of operation (Cutoff, Saturation, and Active modes).

## Approach Used for the Project
A three-stage amplifier is used for the project, with the following order of BJT amplifiers: CC stage, CE stage, and CC stage. The first two stages are arranged as CC-CE because a CE-CC stage combination could not achieve the minimum input resistance value of 20 kΩ. The resistor values for each stage are calculated to meet the specified requirements and ensure proper voltage gains.

## Circuit Configurations and Waveforms
Two circuits were examined for the project: a three-stage amplifier with no load resistance and the same amplifier with a load resistor of 1 kΩ. The circuits were constructed using the Multisim software environment, and their frequency responses were analyzed using the Bode Plot machine. The function generator was set to have a frequency of 20 kHz and an amplitude of 5 milli-Volts peak-to-peak to avoid waveform distortion in the output voltage.

## The report acknowledges that there were some discrepancies in the circuits due to the non-ideal nature of the components used (e.g., β not equal to 150, capacitors with internal resistances, etc.). However, despite these discrepancies, the multistage amplifier design met all the project's specified requirements, including quiescent current and voltage gain.
