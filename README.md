# YouTube Music Player Documentation

Overview
This script allows the user to enter a song name and have that song played on YouTube using the pywhatkit module. It runs in an infinite loop, prompting the user for a new song name each time.

Protip: run ```pyinstaller --onefile 'main.py'``` to convert to exe.

## Modules Used

pywhatkit - Used to play the song on YouTube based on the name entered by the user

## Main Execution Flow

Import pywhatkit module
Start infinite while loop
Prompt user to input a song name
Call pywhatkit.playonyt() to play the song on YouTube, passing the user input as the song name
Repeat steps 3-4 forever
Usage
Run the script and enter a song name when prompted. The song will begin playing on YouTube. Enter another song name to play the next song. Ctrl-C to exit the program.

## Customization

Modify the prompt text in the input() call
Add validation to check if a valid song name was entered
Use a loop other than while True: to control how many songs are played
Add a playlist queue rather than just playing one song at a time
