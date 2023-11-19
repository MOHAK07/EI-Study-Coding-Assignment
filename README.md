# Satellite Control System

The Satellite Control System is a Java application that simulates the control and monitoring of a satellite. This project provides a command-line interface for users to interact with the satellite, execute commands, and observe the state changes.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Command Examples](#command-examples)
- [Design Overview](#design-overview)
- [SOLID Principles and Design Patterns](#solid-principles-and-design-patterns)
- [Logging and Error Handling](#logging-and-error-handling)

## Features

- **Rotation**: Change the satellite's orientation (North, South, East, West).
- **Solar Panels Control**: Activate or deactivate the satellite's solar panels.
- **Data Collection**: Collect data when solar panels are active.
- **Command History**: View the history of executed commands.

## Prerequisites

- Java Development Kit (JDK) installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/satellite-control-system.git](https://github.com/MOHAK07/EI-Study-Coding-Assignment.git)https://github.com/MOHAK07/EI-Study-Coding-Assignment.git
  
2. Navigate to the project directory:

   ```bash
   cd satellite-control-system

3. Compile the Java code:

   ```bash
   javac Main.java
   

## Usage

1. Run the application:
   
   ```bash
   java Main
   
2. Follow the on-screen instructions to interact with the satellite control system.
   

## Command Examples

- Rotate satellite: rotate(North)
- Activate solar panels: activatepanels()
- Deactivate solar panels: deactivate panels()
- Collect data: collectdata()
  

## Design Overview

The system is designed using object-oriented principles and includes the following components:

  - **Satellite Class**: Represents the satellite with methods for rotation, panel activation/deactivation, and data collection.
  - **Command Pattern**: Utilizes a command pattern for executing different satellite commands.
  - **Logging**: Implements logging using the Java util.logging package.
  - **Error Handling**: Includes exception handling for invalid inputs and transient error handling for data collection.
    
    
## SOLID Principles and Design Patterns

The code adheres to SOLID principles, including Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion. Design patterns such as Command and Singleton are also utilized.


## Logging and Error Handling

The application includes a logging mechanism using the SatelliteLogger class. Exception handling is implemented to handle invalid inputs, and transient error handling is incorporated for data collection.




![Satellite_command_system _output](https://github.com/MOHAK07/EI-Study-Coding-Assignment/assets/73355324/53daa18a-33d1-4605-a26e-7cbd4112be97)
