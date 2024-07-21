# AI-Powered Robotic Hand Control

![Handberton Screenshot](https://github.com/user-attachments/assets/c83ccfe5-c7a0-426e-8074-8d3840d6833a)!

Welcome to the **AI-Powered Robotic Hand Control** project repository. This project combines artificial intelligence and robotics to create an interactive and responsive hand control system. The system uses natural language processing (NLP) to interpret user commands and control the movements of a robotic hand, demonstrating the integration of AI in practical applications.

## Test Video

Watch the [test video](https://youtu.be/WfIuchRKQdA) to see the AI-Powered Robotic Hand Control in action.

[![AI-Powered Robotic Hand Control Test Video](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## About the Developers

The AI model, features, and their integration were designed and developed by a team of robotics, machine learning, and backend engineers at [Holberton School Paris](https://www.holbertonschool.fr/campus/paris).

Members of the team:

- **Robotics Engineer**: [Maël Cuny](https://github.com/maelpseudo) - [LinkedIn](https://www.linkedin.com/in/ma%C3%ABl-cuny-054595227/)
- **Machine Learning Engineers**: [Saber Cherif](https://github.com/hakun0) and [Davis Joseph](https://github.com/davisjoseph6) - [LinkedIn](https://www.linkedin.com/in/davisjoseph767/)
- **Backend and Database Engineer**: [Alfred Gibeau--Ahoussinou](https://github.com/alfredgibeau-ahoussinou) - [LinkedIn](https://www.linkedin.com/in/alfred-gibeau-ahoussinou-810a25264/)

Advisors, Consultants, and Sponsors: 
[Holberton School Paris](https://www.holbertonschool.fr/campus/paris)

## Project Description

The **AI-Powered Robotic Hand Control** project aims to create a seamless interface between users and a robotic hand using AI-driven intent recognition. The system understands natural language commands, interprets the user's intent, and performs the corresponding actions with the robotic hand.

### Story of Development

The idea for this project was born out of a desire to explore how AI can be used to control physical devices in an intuitive and user-friendly manner. The journey started with developing a natural language processing model to recognize various commands. Once the model was trained, the next step was integrating it with a robotic hand. This involved extensive testing and fine-tuning to ensure the system responded accurately and promptly to user commands. The project showcases the potential of AI in enhancing human-machine interactions.

### Implemented Features

- **Intent Recognition**: Uses a neural network to classify user commands into predefined intents.
- **Robotic Hand Control**: Commands such as countdowns, calculations, and specific finger movements are executed by the robotic hand.
- **Web Interface**: A simple web interface to input commands and display the system's responses.
- **Mock Arduino Integration**: Simulates Arduino interactions for testing purposes.

### Features to be Implemented

- **Advanced Gesture Recognition**: Implement more complex gestures and sequences.
- **Voice Command Integration**: Allow voice input for hands-free operation.
- **Real-time Feedback**: Provide immediate visual feedback on the web interface about the hand's movements.

### Challenges Faced

One of the biggest challenges was ensuring accurate intent recognition despite the varied ways users can phrase their commands. Training the model with a diverse dataset helped improve accuracy. Integrating the AI model with the robotic hand's control system also required careful handling of real-time data processing and command execution.

## Repository Structure

The repository is organized as follows:

- **AI**
  - `neural_network.py`: Defines and trains the neural network for intent recognition.
  - `intent_recognition_model_v2.h5`, `vectorizer_v2.pkl`, `intent_to_label_v2.pkl`: Trained model, vectorizer, and intent mapping files.
  - `hand_control.py`: Contains functions to control the robotic hand based on recognized intents.
  - `mock_arduino.py`: Simulates Arduino interactions for testing.

- **Root Directory**
  - `app.py`: Flask application to handle web requests and integrate the AI model with the hand control functions.
  - `index.html`: Web interface for user input.
  - `README.md`: Project documentation.
  - `requirements.txt`: List of Python dependencies.

- **static**
  - `script.js`: JavaScript for handling front-end interactions.
  - `style.css`: Styles for the web interface.

---

Thank you for exploring the **AI-Powered Robotic Hand Control** project. Contributions and feedback are welcome to help improve and expand this innovative AI application.
