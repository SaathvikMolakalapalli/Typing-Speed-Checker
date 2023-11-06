## Typing Speed Checker 
This Python script is a typing speed checker application developed using the Pygame library. The application evaluates a user's typing speed, accuracy, and words per minute (WPM) by presenting a random sentence for the user to type and analyzing their performance upon completion.

### Getting Started

1. **Prerequisites**
    - Python installed on your system
    - Pygame library (`pip install pygame`)

2. **Setup**
    - Ensure the necessary image files ('type-speed-open.png', 'background.jpg', 'icon.png') are in the same directory as the Python script.
    - Also, a 'sentences.txt' file containing various sentences for the typing test is required.

3. **Running the Application**
    - Execute the Python script `typing_speed_checker.py`.
    - The application window opens, displaying a sentence for the user to type.

### Usage

- Upon launching the application, users are presented with a sentence to be typed into an input box.
- Start typing the given sentence. Accuracy, time taken, and WPM are calculated upon completion.
- Press 'Enter' to finish typing the sentence.
- Using 'Backspace' removes the last character typed.
- To restart the typing test, click on the "Reset" button.

### Files and Resources

- **Images**
    - `type-speed-open.png`: Opening image for the application
    - `background.jpg`: Background image for the application window
    - `icon.png`: Icon image used in the application

- **Text File**
    - `sentences.txt`: Contains a collection of sentences used for the typing test.

### About the Code

The Python script (`typing_speed_checker.py`) contains an `Application` class that manages the application's functionality. This includes initializing Pygame, handling user input, displaying text and results, calculating performance metrics, and resetting the application for a new typing test.

### Developer Information

- **Developer**: Saathvik
- **Python Version**: Python 3.x
- **Library**: Pygame

### Acknowledgments

- The application was created by Saathvik and is designed to provide a tool for testing and improving typing skills.

This application offers a practical way to evaluate and enhance your typing proficiency.

---
### Sample Image of the Application 
<img width="690" alt="sample" src="https://github.com/SaathvikMolakalapalli/Python-Speed-Typing-Test/assets/83639039/c4102d34-85d0-4899-970a-c57fbd731cd3">
