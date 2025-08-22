# Software-Modeling-using-UPPAL-
# Overview

This project models and verifies a smart home system using UPPAAL
.
The system includes three main functions:

Lighting automation

Authentication and access control

Temperature regulation and alarm system

UPPAAL is used to simulate system behavior and verify that safety and functional requirements hold under all possible execution paths.

### Verified Properties

Lights only turn on at night in automatic mode

Manual and automatic mode cannot be active at the same time

Control panel requires authentication

System is free from deadlocks

AC only activates if temperature > 25°C (set by user)

AC and heater never run simultaneously

Alarm triggers only in valid conditions (night + automatic mode)

...

### How to Run

Install UPPAAL
.

Open .xml in UPPAAL.

Use Simulator to explore behaviors.

Use Verifier with queries.q to check requirements.
