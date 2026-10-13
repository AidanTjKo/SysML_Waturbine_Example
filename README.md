# WATurbine Control System — SysML / MBSE Model

A SysML model of the WATurbine control architecture, created to explore
Model-Based Systems Engineering (MBSE) concepts including system decomposition,
interface modeling, requirements engineering, and traceability.

## System Architecture

The Block Definition Diagram (BDD) decomposes the control system into its
major subsystems: control, sensing, actuation, power, and safety.

![Block Definition Diagram](diagrams/01-bdd.png)

## System Interfaces

The Internal Block Diagram (IBD) models the interfaces between sensors,
the ESP32-based controller, actuators, and safety components.

Information flows include rotor speed, temperature, wind speed,
wind direction, orientation data, and actuator commands.

![Internal Block Diagram](diagrams/02-ibd.png)

## Requirements & Traceability

Functional and safety requirements are linked to the design elements
responsible for satisfying them using SysML `«satisfy»` relationships.

A verification test case demonstrates requirement-to-verification
traceability using `«verify»`.

![Requirements Diagram](diagrams/03-requirements.png)

## Concepts Demonstrated

- SysML Block Definition Diagrams (BDD)
- Internal Block Diagrams (IBD)
- System decomposition
- Ports, connectors, and information flows
- Requirements modeling
- Requirements-to-design traceability
- Verification traceability
- Model-Based Systems Engineering (MBSE)

## Scope

This model focuses on the high-level control architecture of WATurbine.
Detailed PCB-level circuitry, embedded firmware, and mechanical design
are outside the scope of this model.

## Tools

- SysML v1.x
- SysML Studio
