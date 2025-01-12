# Shifra - Your Virtual Assistant

Shifra is an interactive virtual assistant that listens to your voice commands and responds with dynamic actions like opening websites, telling the time or date, and performing web searches. It's built with HTML, CSS, and JavaScript using modern web APIs.

---

## Features

- **Voice Commands**: Recognizes speech to execute tasks.
- **Dynamic Greeting**: Wishes you based on the time of day.
- **Text-to-Speech**: Responds with a human-like voice.
- **Command Execution**:
  - Open websites like YouTube, Google, Facebook, Instagram, and WhatsApp.
  - Provides current time and date.
  - Searches the web for unrecognized commands.

---

## Installation and Usage

### Prerequisites
- A modern browser that supports the `SpeechRecognition` and `SpeechSynthesis` APIs (e.g., Chrome, Edge).

### Steps to Run:
1. Download or clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/shifra-virtual-assistant.git

2. Ensure the following files are in the same folder:

index.html
style.css
script.js
Required assets: logo.jpg, voice.gif, and mic.svg.

3. Open index.html in a browser to start using Shifra.

# File Structure
shifra-virtual-assistant/
├── index.html       # Main HTML structure
├── style.css        # Styling for the virtual assistant
├── script.js        # Core JavaScript functionality
├── logo.jpg         # Logo for the virtual assistant
├── voice.gif        # GIF displayed during speech recognition
├── mic.svg          # Microphone icon for the button
└── README.md        # Project documentation

## Commands You Can Try
Here are some sample commands Shifra understands:

# Greetings:
"Hello" or "Hey"
"Who are you?"

## Website Navigation:
"Open YouTube"
"Open Google"
"Open Facebook"
"Open Instagram"
"Open WhatsApp"

## Utilities:
"What time is it?"
"What's the date?"

## Fallback:
For unknown commands, Shifra will search Google for you.

## How It Works
# Speech Recognition:
Shifra starts listening to your voice when you click the "Talk to Me" button.

# Dynamic Responses:
Based on your voice input, Shifra:

# Responds via text-to-speech.
Executes commands like opening websites or providing the time/date.
Search for Unrecognized Commands:
If Shifra doesn't recognize your command, it opens a Google search for your query.

## Technologies Used
HTML: Structure of the webpage.
CSS: Styling and layout.
JavaScript: Logic for interactivity, speech recognition, and text-to-speech.
Demo
Here’s how Shifra looks and works:
(Include screenshots or GIFs of your project here)

# Known Issues
Speech recognition is not supported on all browsers. Use Google Chrome for the best experience.
Certain commands like "Open Calculator" depend on platform-specific custom protocol support.

# Credits
Developed by Mohan.
Powered by the SpeechRecognition and SpeechSynthesis Web APIs.