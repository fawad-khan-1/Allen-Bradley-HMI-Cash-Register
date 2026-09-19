# Allen-Bradley PLC & HMI Cash Register System

This project implements a PLC-controlled Human-Machine Interface (HMI) for a fictional fast-food restaurant cash register. It was developed as part of a university industrial automation course using the Allen-Bradley HMI platform.

The project combines PLC ladder logic with a two-screen HMI application. The HMI provides the user interface for placing customer orders, displaying quantities and the calculated bill, selecting dine-in or takeout orders, and allowing a manager to modify food prices.

The completed project was originally implemented and tested using physical PLC and HMI equipment available in the university automation laboratory.

## Project Features

- Allen-Bradley PLC programming
- Ladder Logic
- HMI development using Studio 5000 Visual Designer
- Two-screen HMI application
- HMI buttons for placing customer orders
- Display of food items and quantities ordered
- Dine-in and takeout order selection
- Automatic sales tax calculation for dine-in orders
- Display of the calculated food bill
- Manager interface for changing food prices
- HMI buttons and text I/O fields linked to PLC logic
- Physical PLC and HMI implementation

## HMI Operation

The cash register application uses two HMI screens.

### Customer Order Screen

The first screen provides the main cash register interface.

It allows the operator to:

- View food items
- View the quantity ordered
- Place a customer's order
- Select dine-in or takeout
- View the calculated food bill

For dine-in orders, the program applies a 6.25% sales tax. Takeout orders do not have the sales tax applied.

### Manager Price Screen

A button on the first screen provides access to a second HMI screen.

The second screen allows the manager to change food prices using input fields.

A navigation button allows the user to return from the manager screen to the main ordering screen.

## PLC and HMI Integration

The project began with the cash-register control logic implemented using Ladder Logic.

The PLC logic was then linked to the HMI so that the program's inputs and outputs could be controlled and displayed through HMI elements such as buttons and text I/O fields.

This project was a variation of an earlier wired cash-register exercise in which the inputs came from physical breadboard buttons and information was displayed directly through the program. In this version, those interactions were moved to the HMI.

## Technologies

- Allen-Bradley PLC
- RSLogix 5000 / Studio 5000
- Studio 5000 Visual Designer
- Ladder Logic
- HMI Programming
- PLC/HMI Integration
- HMI Buttons
- Text I/O Fields
- Industrial Automation

## Repository Contents

This repository contains original project files and documentation preserved from the university laboratory project.

### Original Project Files

- `Cash_Register_with_HMI.ACD` – original Allen-Bradley PLC project file
- `Cash_Register_HMI.vpd` – original project file associated with the HMI implementation

The original project files have been preserved from the completed university project.

The required Allen-Bradley development software is not currently installed on my personal computer, so these files are maintained in this repository as original project artifacts.

### Project Documentation

- `Cash Register HMI Allen Bradley.pdf` – documentation of the HMI and PLC implementation
- `Cash Register Wired AB.pdf` – documentation associated with the earlier wired Allen-Bradley cash-register implementation

## Original Lab Documentation

The repository also includes a PDF copy of the original HMI laboratory report written when the project was completed.

The report documents:

- The objective of the Allen-Bradley HMI project
- The relationship between the Ladder Logic program and HMI
- The two-screen HMI design
- Customer ordering functionality
- Dine-in and takeout operation
- 6.25% dine-in sales tax
- Manager food-price configuration
- HMI buttons and text I/O fields
- Studio 5000 Visual Designer
- The original learning outcomes

The original report is included to preserve documentation of the project as it existed when it was developed.

## Hardware Testing

The completed project was implemented and tested using physical Allen-Bradley PLC and HMI equipment in the university automation laboratory.

The project therefore represents an actual hardware implementation rather than only an offline PLC/HMI programming exercise.

## Demonstration

A video recording was made of the completed HMI application operating on the laboratory equipment when the project was originally completed.

The original video may be added to this repository as an additional demonstration of the system.

## Project Purpose

The purpose of this project was to gain hands-on experience developing an HMI application using the Allen-Bradley platform and integrating the HMI with PLC Ladder Logic.

The project provided practical experience with PLC programming, HMI development, PLC/HMI interaction, user-interface design, and implementation on physical industrial automation hardware.