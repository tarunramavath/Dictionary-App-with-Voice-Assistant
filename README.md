# Dictionary App with Voice Assistant

This is a simple dictionary application with a graphical user interface (GUI) built using Python's `tkinter` library. The app allows users to input a word and get its meaning, which is then displayed on the screen and spoken out loud using the `pyttsx3` text-to-speech engine. It also leverages the `nltk` (Natural Language Toolkit) library to fetch word definitions from the WordNet lexical database.

## Features

- **Word Lookup**: Users can enter a word, and the app will fetch its meaning from WordNet.
- **Text-to-Speech**: The meaning of the word is spoken aloud using the `pyttsx3` library.
- **Synonyms Finder**: The app also includes a function to find synonyms of a word (although it’s not yet integrated into the UI).
- **Easy-to-Use GUI**: Built with `tkinter`, the app features a clean, user-friendly interface.

## Dependencies

The following Python libraries are required to run this project:

- `tkinter`: For creating the GUI (included in Python by default).
- `pyttsx3`: For the text-to-speech functionality.
- `nltk`: For fetching word meanings from WordNet.


## Usage

1. Launch the application.
2. Enter a word into the input field and press the "Speak Meaning" button.
3. The app will display the meaning and speak it aloud.


![Screenshot 2024-09-17 154020](https://github.com/user-attachments/assets/3e2e36a5-d4e9-40f1-86c3-d0ae56d3961c)
