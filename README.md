# task3 : Voice-to-Voice AI Assistant

## Description

This project is a smart Voice-to-Voice AI Assistant that allows the user to speak through the microphone, converts the speech into text, sends the text to the Gemini AI model, receives an intelligent response, and then converts the response back into speech.

The project was built using HTML, CSS, JavaScript, PHP, and the Gemini API.

---

## How It Works

The application works in three main steps:

### 1. Speech-to-Text

The user clicks the microphone button and speaks.

The browser uses the Web Speech Recognition API to convert the user's voice into written text.

### 2. AI Response Generation

The converted text is sent from JavaScript to the PHP backend.

The PHP file sends the user's message to the Gemini API and receives an intelligent response.

### 3. Text-to-Speech

The response from Gemini is displayed in the chat interface.

The browser uses the Speech Synthesis API to read the response aloud to the user.

---

## Features

- Arabic voice recognition
- Voice-to-text conversion
- AI-generated responses using Gemini
- Text-to-speech conversion
- Arabic chat interface
- Microphone status indicator
- Error handling
- Responsive design
- Secure API key handling through PHP

---

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- Google Gemini API
- Web Speech Recognition API
- Speech Synthesis API
- XAMPP

---

## Project Structure

```text
voice-assistant/
│
├── api/
│   └── chat.php
│
├── index.html
├── style.css
├── app.js
├── config.example.php
├── .gitignore
├── .htaccess
└── README.md
```

---

## How to Run

1. Install XAMPP.
2. Copy the project folder into the `htdocs` directory.
3. Start Apache from the XAMPP Control Panel.
4. Create a `config.php` file by copying `config.example.php`.
5. Open `config.php` and add your own Gemini API key.
6. Open your browser and go to:

```
http://localhost/chat%20bot%20exmample/
```

7. Allow microphone access.
8. Click the microphone button and start speaking.

---

## Configuration

Before running the project:

1. Copy `config.example.php` and rename it to `config.php`.
2. Open `config.php`.
3. Add your own Gemini API key.
4. Save the file.
5. Run the project using XAMPP.

> **Note:** The `config.php` file is not included in this repository because it contains a private Gemini API key. A template file (`config.example.php`) is provided instead.
