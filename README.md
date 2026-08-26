# Mindwell

Mindwell is a caring and empathetic AI companion designed to listen, validate feelings, and provide gentle, supportive responses. Built using Flask, Google's Gemini AI, and Google Cloud Text-to-Speech, it offers both text-based chat and voice interactions to help you feel heard and supported.

## Features

- **Empathetic Conversations:** Powered by Gemini 1.5 Pro to provide warm, non-judgmental, and comforting replies.
- **Voice Interactions:** Includes high-quality voice synthesis via Google Cloud Text-to-Speech (WaveNet voices) for a more personal touch.
- **Simple, Accessible UI:** Features both text chat and voice interfaces, designed with a focus on simplicity and user comfort.

## Prerequisites

To run this project, you will need:
- Python 3.x
- A Google Gemini API Key
- A Google Cloud Service Account JSON file with access to the Text-to-Speech API

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gargaryan777/Mindwell_chat.git
   cd Mindwell_chat
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   - Set `GEMINI_API_KEY` to your Google Gemini API key.
   - Set `GOOGLE_APPLICATION_CREDENTIALS` to the path of your Google Cloud service account JSON file.

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://localhost:5000` to interact with Mindwell.

## Deployment

This application is ready to be deployed to platforms like Render. Make sure to securely configure your API keys and service account JSON files as secret files or environment variables on your hosting provider.

## License
[MIT](LICENSE)
