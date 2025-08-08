# Rubik's Cube Solver

Java program by **Rida Fatima**, utilizing a Swing GUI to find and display a solution to a given scramble for a Rubik's Cube.

## Description

This program finds a valid solution to a scrambled Rubik's Cube using the beginner's method. While this method generates longer solutions compared to advanced algorithms, it is easier for beginners to understand and learn intuitively.

The goal of this project is to help beginners learn to solve the cube by:

* Allowing input through either **scramble notation** or **manual color entry**.
* Displaying and animating the solution in a 2D format.
* Providing controls to pause, start, rewind, and fast-forward the animation.
* Showing the move sequence, with black text for moves yet to be performed and red text for moves already completed.

## Requirements

* Java SDK 1.8 or later

## Installation

1. Download and unzip the project.
2. Open a terminal and navigate to the `src` folder.
3. Compile and run:

   ```bash
   javac CubeDisplayer.java
   java CubeDisplayer
   ```

## Usage

Before using this program, learn the standard Rubik's Cube notation [here](https://ruwix.com/the-rubiks-cube/notation/).

**Modes:**

1. **Text Scramble Mode**

   * Enter a scramble in the text field and click **APPLY**.
   * Click **RANDOM** to generate a random scramble.
   * Control animation playback and speed using the buttons and slider.
   * Use **Mode Selection** in the menu bar to switch modes.

2. **Color Input Mode**

   * Select a cube face from the combo box and fill in the colors.
   * Use **RESET** to clear all inputs.
   * Once all 6 faces are entered, click **PROCEED** to view the solution.

### Screenshots:

*Text Scramble Mode*
![Text Scramble Mode](/images/Text.jpeg)

*Color Input Mode – Selection*
![Color Input Mode](/images/ColorInput.jpeg)

*Color Input Mode – Solution*
![Color Input Solution](/images/ColorSolution.jpeg)

## License

This project is licensed under the MIT License.
**Copyright © 2025 Rida Fatima** — see `LICENSE.txt` for details.
