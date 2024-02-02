# Text to Speech Converter

## Overview
This project is a simple text-to-speech converter built using Python and tkinter GUI library. It allows users to input text, select voice gender and speed, and either play the generated speech or download it as an audio file.

## Prerequisites
- Python 3.x
- Tkinter
- Pyttsx3
- gTTS (Google Text-to-Speech)
- Playsound

## Installation
1. Install required packages:
   
   `pip install pyttsx3 gtts playsound `

1.  Clone the repository:

    

    `git clone <repository_url>`

2.  Navigate to the project directory:

   

    `cd <project_directory>`

Usage
-----

1.  Run the application:

    bashCopy code

    `python text_to_speech_converter.ipynb`

2.  Enter the desired text in the text box.

3.  Select the voice gender (Male/Female) and speed (Fast/Medium/Slow).

4.  Click the "Play" button to listen to the generated speech.

5.  Click the "Download" button to save the speech as an audio file.

Directory Structure
-------------------

-   `main.py`: Main Python script for the text-to-speech converter.
-   `image/`: Directory containing image resources for the GUI.

Components
----------

-   `pyttsx3`: Library for text-to-speech conversion.
-   `gtts`: Google Text-to-Speech library for generating speech from text.
-   `playsound`: Library for playing audio files.

Contributing
------------

Contributions are welcome! Please submit pull requests or open issues for any improvements or bug fixes.

License
-------

This project is licensed under the MIT License - see the LICENSE file for details.
