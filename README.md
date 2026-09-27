# Series Resistors - Current Comparison Experiment

## Objective
To understand how resistors connected in series affect total resistance and current in a circuit.

## Circuit
A 9V power supply was used with:
- Circuit A: One 1kΩ resistor
- Circuit B: Two 1kΩ resistors connected in series

A multimeter was connected in series to measure current.

## Concept

For resistors connected in series:

R_total = R1 + R2

Using Ohm's Law:

I = V / R_total

## Design Calculation

### Circuit A - One 1kΩ Resistor

R_total = 1kΩ

I = 9V / 1000Ω

I = 0.009A = 9mA

### Circuit B - Two 1kΩ Resistors

R_total = 1kΩ + 1kΩ

R_total = 2kΩ

I = 9V / 2000Ω

I = 0.0045A = 4.5mA

## Simulation Results

| Circuit | Total Resistance | Calculated Current | Measured Current |
|---|---:|---:|---:|
| One 1kΩ resistor | 1kΩ | 9mA | 9.00mA |
| Two 1kΩ resistors | 2kΩ | 4.5mA | 4.50mA |

## Observation

When a second 1kΩ resistor was added in series, the total resistance increased from 1kΩ to 2kΩ.

As the resistance increased, the circuit current decreased from 9.00mA to 4.50mA.

## What I Learned

- Resistors in series add together.
- The same current flows through all components in a series path.
- Increasing total resistance decreases current when the supply voltage remains constant.
- Calculated and simulated results matched.

## Engineering Lesson

Series resistors can be used to control current and create desired resistance values in electronic circuits.

## Tools Used

- Tinkercad Circuits
- Multimeter
- 9V Power Supply
- 1kΩ Resistors
