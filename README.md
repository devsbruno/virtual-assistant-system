# Virtual Assistant System

This repository contains a complete Virtual Assistant System built from scratch using Natural Language Processing (NLP) techniques in Python. The system includes modules for text-to-speech, speech-to-text, and command-based actions. It can perform tasks such as searching Wikipedia, opening YouTube, and displaying the nearest pharmacy location based on voice commands.

## Project Overview

The Virtual Assistant System is designed to:
- Convert text to speech (TTS) using the gTTS library.
- Convert speech (from an uploaded audio file) to text using the SpeechRecognition library.
- Process voice commands to trigger specific automated functions such as:
  - Searching for information on Wikipedia.
  - Opening YouTube.
  - Showing the location of the nearest pharmacy via a Google Maps search.

This project is developed to run on Google Colab. Due to Colab's limitations with direct microphone input, the system prompts the user to upload a WAV audio file containing their command.

## Features

- **Text-to-Speech (TTS):** Converts text into audible speech using the Google Text-to-Speech (gTTS) library.
- **Speech-to-Text (STT):** Converts spoken language from an uploaded audio file to text using the SpeechRecognition library.
- **Command Processing:** Recognizes specific commands (e.g., "Wikipedia", "YouTube", "pharmacy") and triggers corresponding actions.
- **Interactive Workflow:** Designed for interactive use on Google Colab, allowing users to upload audio files for speech recognition.

## Technologies Used

- **Python 3.x**
- **SpeechRecognition** for converting speech to text.
- **gTTS (Google Text-to-Speech)** for converting text to audio.
- **Wikipedia API** for fetching summaries from Wikipedia.
- **Google Colab** for interactive execution.
- **Webbrowser Module** (or printed URLs) to simulate opening websites.

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/virtual-assistant-system.git
   cd virtual-assistant-system
   ```

2. **Open the Notebook in Google Colab:**

   Open `virtual_assistant_system.ipynb` in Google Colab.

3. **Execute the Cells:**

   Follow the instructions in the notebook:
   - The assistant will greet you and ask you to upload a WAV audio file containing your voice command.
   - After processing your command, the assistant will perform the corresponding action (e.g., search Wikipedia, open YouTube, or provide a link for the nearest pharmacy).

## Project Structure

```
virtual-assistant-system/
├── virtual_assistant_system.ipynb  # Main Colab Notebook for the Virtual Assistant System
└── README.md                       # Project documentation
```

## Notes

- This project is intended as an educational example. For production use, consider integrating with more robust voice recognition systems and APIs.
- Since Google Colab does not support direct microphone input, users must upload an audio file containing their voice command.
- The system uses printed URLs for actions like opening YouTube or displaying the nearest pharmacy location, as Colab does not support direct browser redirection.


## Acknowledgments

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/)
- [Wikipedia API](https://pypi.org/project/wikipedia/)
- [Google Colab](https://colab.research.google.com/)

