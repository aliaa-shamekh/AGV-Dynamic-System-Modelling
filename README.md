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

\cases{R\index{4}=\frac{W\index{cart}|4}\power{}||F\index{4}= I\index{4}\frac{a|r\power-index{2|4}} + 𝜇\index{rr4} R\index{4}||F\index{3}=m\index{cart} a +4F\index{4}||R\index{2}= \frac{F\index{3} y + W\index{agv} x|2L}||R\index{1}= W\index{agv} - 2R\index{2}||F\index{2}= I\index{2} \frac{a|r\power-index{2|2}} + 𝜇\index{rr2} R\index{2}||F\index{1}= m\index{agv} a +2F\index{2} + F\index{3}||I\index{2} =I\index{4} =\frac{1|2} m\index{wheel} r\power-index{wheel|2}}

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
