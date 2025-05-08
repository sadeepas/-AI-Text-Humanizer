# -AI-Text-Humanizer
A powerful desktop application built with Python and Tkinter that transforms robotic or AI-generated text into a more natural, human-sounding version using Hugging Face Transformers and TextBlob. This tool is ideal for content creators, writers, or developers who want to humanize raw AI-generated outputs effortlessly.



✨ AI Text Humanizer
A powerful desktop application built with Python and Tkinter that transforms robotic or AI-generated text into a more natural, human-sounding version using Hugging Face Transformers and TextBlob. This tool is ideal for content creators, writers, or developers who want to humanize raw AI-generated outputs effortlessly.

🧠 Features
🔁 Paraphrasing with Transformers (t5_paraphraser model)

✅ Spelling correction using TextBlob

📋 Copy, ✂️ Cut, 💾 Download output text easily

💻 Responsive, modern, and stylish GUI

🧵 Background threading for non-blocking UI during processing

🖼️ UI Preview
Dark-themed interface

Animated hover buttons

Smooth and intuitive user experience

🛠️ Requirements
Make sure the following Python packages are installed:

bash

pip install transformers textblob nltk
Also download the NLTK data required by TextBlob:

python
import nltk
nltk.download('punkt')

🚀 How to Run
Clone or download this repository.

Make sure all dependencies are installed.

Run the script:
bash
python humanizer_app.py

📁 File Structure
bash
humanizer_app.py  # Main application file

📌 Notes
Internet connection is required as the app uses Hugging Face's transformer pipeline.

The model used: ramsrigouthamg/t5_paraphraser

Make sure to use appropriate text inputs for best results (English language supported).

📸 Example Use Case
Input:

sql

The quick brown fox jumps over the lazy dog.
Humanized Output:

css

A swift brown fox leaped over a sleepy dog.
