﻿# ARK-AI-Assistant

ARK AI Assistant is a Python-based virtual assistant capable of performing various tasks such as telling the time, cracking jokes, searching Wikipedia, and much more. This lightweight assistant leverages popular Python libraries to provide a fun and interactive experience. Get started with ARK AI Assistant and customize it to meet your needs!

---

## Features

- **Speech Output:** ARK AI can speak responses using text-to-speech.
- **Voice Recognition:** Interact with ARK AI through voice commands.
- **Web Browsing:** Open websites directly through voice commands.
- **Wikipedia Search:** Fetch summaries from Wikipedia for quick information.
- **Jokes:** Lighten the mood with programming jokes.
- **Time Query:** Ask ARK AI for the current time.

---

## Prerequisites
Ensure Python is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).

---

## Installation

Clone the repository and install the required modules:

```bash
# Clone the repository
git clone https://github.com/yourusername/ARK-AI-Assistant.git

# Navigate to the project directory
cd ARK-AI-Assistant

# Install required modules
pip install -r requirements.txt
```

Alternatively, install the required modules individually:

### Required Modules

#### 1. **pyttsx3**
A text-to-speech conversion library.

```bash
pip install pyttsx3
```

#### 2. **SpeechRecognition**
A library for speech-to-text conversion.

```bash
pip install SpeechRecognition
```

#### 3. **webbrowser**
A built-in Python module to open web browsers. No installation required.

#### 4. **wikipedia**
Fetch summaries and articles from Wikipedia.

```bash
pip install wikipedia
```

#### 5. **pyjokes**
A library to generate programming-related jokes.

```bash
pip install pyjokes
```

#### 6. **datetime**
A built-in Python module to handle date and time. No installation required.

---

## Usage

Run the following command to start ARK AI Assistant:

```bash
python FlaskApp.py
```

ARK AI will prompt you with voice input instructions. Simply speak your command, and ARK AI will respond appropriately.

### Example Commands

- "What time is it?"
- "Tell me a joke."
- "Search Wikipedia for Python programming."
- "Open YouTube."

---

## Contributing

We welcome contributions! To contribute:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License.

---

## Future Enhancements

- Add support for weather queries.
- Include task reminders and to-do list management.
- Integrate with home automation systems.
- Support for multiple languages.

---

Enjoy using ARK AI Assistant!


