# Arduino Controlled Racing Game

A physical-button racing game built using Arduino Uno, Python, Pygame, and Serial Communication.

## Features

- Physical LEFT button
- Physical RIGHT button
- Third button for Brake/Boost
- Arduino Uno controller
- Real-time serial communication
- Moving traffic obstacles
- Score system
- Speed system
- Collision detection

## Hardware Used

- Arduino Uno
- 3 Push Buttons
- Breadboard
- Jumper Wires
- USB Cable

## Software Used

- Python
- Pygame
- PySerial
- Arduino IDE

## Controls

- Button 1 → Left
- Button 2 → Right
- Button 3 → Brake / Boost

## Working

The Arduino reads the three physical push buttons and sends commands such as LEFT, RIGHT, and BRAKE to the laptop through serial communication.

Python receives these commands using PySerial and controls the racing game created using Pygame.

## Run the Game

Install dependencies:

```bash
pip install pygame pyserial
