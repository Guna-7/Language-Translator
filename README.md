# Language Translation Tool 🈯

A Tkinter-based desktop application for translating text between multiple languages using Google Translate API (via googletrans), with extra features like text-to-speech, clipboard integration, and language auto-detection.

# 🚀 Features

Multi-language Translation
Translate text between 100+ languages using Google Translate.

Language Auto-Detection
Automatically detect the source language.

Text-to-Speech (TTS)
Hear the translated text using Python's pyttsx3 engine.

Clipboard Support
Easily paste input from the clipboard and copy the translation.

Swap Languages
Switch between source and target languages with one click.

Clean, Modern GUI
Built with Tkinter and ttk widgets for a smooth user experience.

# 🛠️ Tech Stack

Python 3.x

Tkinter – GUI framework

googletrans – Language translation

pyttsx3 – Text-to-speech

pyperclip – Clipboard operations

threading – Non-blocking translation & speech

# 📦 Installation

Clone the Repository

git clone https://github.com/your-username/language-translation-tool.git
cd language-translation-tool


# Install Dependencies

pip install googletrans==4.0.0-rc1 pyttsx3 pyperclip requests


Run the Application

python translator.py

📷 Screenshots

(Add screenshots of your UI here for a better portfolio presentation.)

# ⚙️ How It Works

Select Source and Target Languages (or choose Auto-Detect for source).

Enter/Paste Text in the input area.

Click Translate to get the translation.

Optionally:

Click 🔊 Speak to listen to the translation.

Click Copy to copy translation to clipboard.

Click ⇄ to swap languages.
