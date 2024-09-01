# Project: HaimOzer's Guessing Game

# Description:
The Guessing Game is a simple console-based game written in C. The game challenges the player to guess a randomly generated number within a limited number of attempts. The game is designed to run on a Microchip microcontroller, utilizing UART communication for user interaction and a hardware timer to generate the random number.

# How to Play:
1. Start the Game: When the game starts, you will be greeted with a welcome message.
2. Make a Guess: You have seven attempts to guess the correct number. Enter your guess using the UART terminal.
3. Feedback: After each guess, the game will provide feedback:
   - If your guess is too high, you will be informed that it's too high.
   - If your guess is too low, you will be informed that it's too low.
4. Win Condition: If you guess the correct number within the allowed attempts, the game will congratulate you and record a win.
5. Lose Condition: If you fail to guess the correct number within seven attempts, the game will reveal the correct number and record a loss.

# Features:
- Random Number Generation: The game uses a hardware timer to generate a random number at the start of each round.
- Attempt Counter: You have a total of seven attempts to guess the correct number.
- Score Tracking: The game tracks the number of wins and losses throughout the session.

# How to Build and Run:
1. Environment Setup: Ensure that you have the necessary tools to build and flash code onto a Microchip microcontroller.
2. Build the Project: Compile the source code using the appropriate compiler for your Microchip microcontroller.
3. Flash the Microcontroller: Use the appropriate flashing tool to upload the compiled code onto your microcontroller.
4. Connect UART Terminal: Open a UART terminal on your computer connected to the microcontroller's UART interface.
5. Play the Game: Follow the on-screen instructions in the UART terminal to play the game.

# Dependencies:
- Microchip MPLAB X IDE (or equivalent)
- A Microchip microcontroller with UART support
- UART terminal software (e.g., PuTTY, Tera Term)
