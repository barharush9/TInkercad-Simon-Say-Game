# Simon Says Game

This **Simon Says** game is developed using **Tinkercad** and features a sound-based user interface (UI) that lights up the correct color LED based on detected sound frequencies. The UI is developed using **JavaScript** to handle real-time interaction with the game.

## Features

- **Sound Frequency Detection**: The game listens for specific sound frequencies and lights up the corresponding LED.
- **Color Mapping**:
  - **Red**: Detects frequencies between 100-200 Hz.
  - **Green**: Detects frequencies between 200-350 Hz.
  - **Blue**: Detects frequencies between 351-450 Hz.
  - **Yellow**: Detects frequencies between 451-550 Hz.
- **JavaScript-Based UI**: The game's interface is built using JavaScript, allowing for dynamic interaction with the player based on the detected sound frequencies.
- **Interactive Gameplay**: Players interact with the game by producing sounds, and the system responds by lighting up the LED that matches the sound's frequency.

## Project Setup

This project was created in **Tinkercad** and uses basic electronic components like LEDs, a microphone, and an Arduino board for hardware interaction.

### Components:
- **Arduino Uno**: Microcontroller for handling game logic.
- **Microphone**: Detects sound input.
- **LEDs**: Red, Green, Blue, and Yellow LEDs are used to indicate correct sounds.
- **Resistors**: Used to limit current for each LED.

### Requirements

To run this project, you need to create an `.env` file with the necessary credentials for accessing **Tinkercad**. The `.env` file should contain the following information:

