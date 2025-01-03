                                                              Piano Tiles Bot

This project implements a bot to automatically play the popular game "Piano Tiles." Using Python's pyautogui library, the bot identifies the black tiles on the game screen and simulates mouse clicks to play the tiles in real time.

                                                           Cursor Position Tracker

Retrieves the current position of the cursor on the screen to help identify the tile locations.


                                                              Click Functionality

A custom click function is defined using the win32api and win32con libraries to simulate mouse clicks at specific screen coordinates.



                                                        Tile Detection and Gameplay Automation:

Continuously scans specific coordinates on the screen to detect black tiles based on their pixel color.

Simulates a mouse click when a black tile is detected.

Uses the keyboard library to allow the user to stop the bot by pressing the "q" key.



                                                                   How to Use

Install the required libraries:

pip install pyautogui keyboard

Run the script and position the cursor over the game tiles to determine their coordinates.

Replace the hardcoded coordinates in the script with the actual tile positions from your game.

Start the game and run the bot script. Press "q" to stop the bot.

Notes

This script assumes a fixed screen resolution and tile positions. You may need to adjust the pixel coordinates for your specific setup.

The bot relies on detecting black tiles by their pixel color. Ensure proper lighting and contrast for accurate detection.
the gameplay link->https://drive.google.com/file/d/1CO6e6mrzEgMFCi6k9Hzt4w-jsUcOVyYF/view?usp=sharing

