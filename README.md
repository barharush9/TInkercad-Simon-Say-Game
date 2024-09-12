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

TINKERCAD_USER=[your_tinkercad_username] TINKERCAD_PASS=[your_tinkercad_password]

This file allows the game to integrate with your **Tinkercad** environment and access the required components and settings.

## How to Play

1. **Make a sound**: Use your voice or an external tone generator.
2. The system will detect the frequency of the sound and light up the corresponding LED based on the frequency range.
3. Repeat the process to match all tones correctly.

## Project Presentation

Below are images that provide an overview of the Simon Says game in chronological order:

1. ![Slide 1](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0001.jpg)
2. ![Slide 2](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0002.jpg)
3. ![Slide 3](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0003.jpg)
4. ![Slide 4](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0004.jpg)
5. ![Slide 5](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0005.jpg)
6. ![Slide 6](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0006.jpg)
7. ![Slide 7](/photos%20for%20simon%20game/Simon%20Say%20-%20Game%20Presentation_page-0007.jpg)

## Additional Information

For more detailed information, please refer to the project **presentation** or **poster**. These materials provide further insight into the design and functionality of the game.

## Author

Developed by [Your Name] as part of a Tinkercad project.

