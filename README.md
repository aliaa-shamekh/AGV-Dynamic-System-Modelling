# AGV for Material Handling – Dynamic System Modelling

## Overview

This project focuses on the modelling and simulation of an Automated Guided Vehicle (AGV) designed for material handling.

The project was developed as part of the **Modelling and Simulation of Dynamic Systems** course.

## My Contribution

I was responsible for the **mathematical modelling** of the AGV system, including:

- Developing the system schematics
- Deriving the equations of motion
- Modelling rolling resistance
- Analysing drive-wheel tractive effort
- Modelling the towing/load resistance
- Relating the motor torque, wheel dynamics, and external resistive forces

## System

The AGV consists of a drive wheel and trailing/load wheels and is designed to tow a material-handling cart.

The model considers the main forces and moments affecting the vehicle's forward motion, including rolling resistance, motor torque, wheel dynamics, and the towing load.

## Modelling

### System Schematics & Equations of Motion

The main equations used in the mathematical model are:

$$
R_4 = \frac{W_{cart}}{4}
$$

$$
F_4 = I_4\frac{a}{r_4^2} + \mu_{rr4}R_4
$$

$$
F_3 = m_{cart}a + 4F_4
$$

$$
R_2 = \frac{F_3y + W_{agv}x}{2L}
$$

$$
R_1 = W_{agv} - 2R_2
$$

$$
F_2 = I_2\frac{a}{r_2^2} + \mu_{rr2}R_2
$$

$$
F_1 = m_{agv}a + 2F_2 + F_3
$$

The wheel rotational inertias are defined as:

$$
I_2 = I_4 =
\frac{1}{2}m_{wheel}r_{wheel}^2
$$

### Rolling Resistance

The model considers the energy dissipated due to deformation of the rubber tire against the rigid floor. The resulting shift in the normal force produces a rolling resistance moment that must be overcome by the drive system.

### Tractive Effort

The drive-wheel friction generates the forward force required to move the AGV. The motor torque must overcome the wheel's rotational dynamics and the resistance caused by the trailing load.

### Towing Load

The total tractive effort must overcome the resistance from the rear wheels and the load being towed by the AGV.

## Project Context

**Course:** Modelling and Simulation of Dynamic Systems  
**Project:** AGV for Material Handling

 **Instructor:** Lobna Abo Serre

## Tools

- MATLAB
- Simulink
- MathCha
