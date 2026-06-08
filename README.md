Objective

The objective of this project is to understand how keyboard input can be monitored and recorded. The program captures keystrokes and stores them in a log file for analysis and educational purposes.

Description

A keylogger is a software application that records keyboard inputs. In this project, the program monitors key presses and saves them to a text file. The recorded data can then be reviewed to study user input patterns and event handling mechanisms.

Features
Records keyboard keystrokes.
Logs each key press.
Saves logged data to a text file.
Simple and lightweight implementation.
Demonstrates file handling and event monitoring concepts.
Requirements
Python 3.x
Required libraries (if used):
pynput
keyboard
Working Principle
The program starts and waits for keyboard input.
Every key pressed by the user is detected.
The detected key is converted into a readable format.
The key information is appended to a log file.
The log file stores all recorded keystrokes for later review.
