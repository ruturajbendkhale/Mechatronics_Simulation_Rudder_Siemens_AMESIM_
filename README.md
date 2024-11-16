# Tanker Steering Gear Design Project

## Overview

This project focuses on developing a fundamental design for a steering gear system for tankers with a carrying capacity exceeding 100,000 tonnes DWT. The design adheres to DNV_GL criteria, ensuring safety and reliability in marine applications.

## Key Features

- Designed for tankers >100,000 tonnes DWT
- Compliant with DNV-GL standards
- Electro-hydraulic steering system
- PI Controller for precise rudder angle control

## System Components

1. Control Unit: Manages power unit operations and rudder angle adjustments
2. Power Unit: Provides hydraulic power to actuators
3. Hydraulic Actuators: Convert hydraulic pressure into rudder movement
4. Rudder: Primary control surface for ship steering
5. Tiller Arm: Converts linear motion to rotary motion for the rudder stock

## Technical Specifications

- Rudder Area: 61.8752 m²
- Rudder Weight: 20.9486 tonnes
- Tiller Arm Length: 0.9 meters
- Maximum Torque: 4.6016e+04 N-m

## Performance Requirements

- 35° port to 35° starboard (and vice versa) in ≤28 seconds at maximum continuous rated shaft rpm
- 15° port to 15° starboard (and vice versa) in <60 seconds at half nominal maximum speed or 7 knots (whichever is greater)

## Control System

The steering gear utilizes a PI (Proportional-Integral) controller for accurate rudder angle management:

- Reference Signal: Desired rudder angle
- Feedback Signal: Actual rudder angle
- Controller Output: Manages the Hydraulic Power Unit

## Simulation Models

The project includes AMESim and Siemens simulation models demonstrating the PID controller implementation for the steering system.

## Contributors

- Ruturaj Rajendra Bendkhale
- Yashwant Rao

## Acknowledgments

Special thanks to Prof. Norbert Buro for guidance throughout the project.
