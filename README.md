# PatroGalaxy: An Embedded Systems Space Shooter for BitDogLab

## Overview

PatroGalaxy is a classic space shooter game developed specifically for the [BitDogLab](https://github.com/BitDogLab/BitDogLab) embedded systems learning platform. It serves as a practical demonstration of embedded programming techniques using the Raspberry Pi Pico W microcontroller.

## Videos

### Quick Gameplay Demo

See PatroGalaxy in action!

[![PatroGalaxy Demo Video](http://img.youtube.com/vi/mwKkf3WDbOc/0.jpg)](https://www.youtube.com/watch?v=mwKkf3WDbOc)

### Official Project Presentation (MNR 2025)

Watch the full project presentation (in Portuguese), created for the Brazilian National Robotics Exhibition.

[![PatroGalaxy MNR Presentation](http://img.youtube.com/vi/vXHZ5OMD9kg/0.jpg)](https://www.youtube.com/watch?v=vXHZ5OMD9kg)

This project showcases the capabilities of the BitDogLab, including its OLED display, analog stick, action button, and flash memory, within the engaging context of a retro-style arcade game.

## Features

- **Classic Space Shooter Gameplay:** Navigate a spaceship, dodge asteroids, and shoot enemies to achieve the highest score.
- **BitDogLab Integration:** Leverages the platform's integrated OLED display (SSD1306), analog stick, and action button for a complete interactive experience.
- **High Score Persistence:** Stores the player's high score in the Raspberry Pi Pico W's flash memory, allowing for persistent record keeping.
- **Progressive Difficulty:** The game's difficulty increases over time, providing an engaging and challenging experience.
- **Modular Code Design:** The code is well-structured and modular, making it easy to understand, modify, and extend with new features.
- **Clean Code:** Well-documented for simple understanding.

## Hardware Requirements

- [BitDogLab](https://github.com/BitDogLab/BitDogLab) platform
- Raspberry Pi Pico W microcontroller (integrated in the BitDogLab)

## Software Requirements

- Raspberry Pi Pico SDK
- Any IDE that supports C code compilation

## How to Build and Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/luisfpatrocinio/PatroGalaxy.git
   cd PatroGalaxy
   ```

2. **Configure the build environment:** Follow the instructions for setting up the Raspberry Pi Pico SDK.
3. **Compile the code:** Use the appropriate build commands for your environment.
4. **Flash the code onto the Raspberry Pi Pico W:** Use the appropriate tools for flashing the code onto the microcontroller.
5. **Enjoy PatroGalaxy on your BitDogLab!**

## Code Structure

The codebase is organized into the following key modules:

- **`src/core/`**: Core game logic and initialization.
- **`src/drivers/`**: Hardware drivers and abstractions (analog stick, OLED display, save system).
- **`src/entities/`**: Game entities and their behavior (player, asteroids, bounding box).
- **`src/graphics/`**: Graphical rendering functions.
- **`src/assets/`**: Game assets such as images, and fonts.

## Contributing

This project is intended to be a valuable resource for the embedded systems community. I encourage improvements to be implemented by anyone. Feel free to:

- Submit bug reports
- Suggest new features
- Contribute code improvements via pull requests
- Translate the documentation to other languages

## Contact

If you have any questions or feedback, feel free to contact me:

- [Github](https://github.com/luisfpatrocinio)

## Author

Luis Felipe dos Santos Patrocinio
