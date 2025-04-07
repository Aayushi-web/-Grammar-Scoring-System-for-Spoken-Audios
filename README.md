# 🎧 Grammar Scoring System for Spoken Audios

This project transcribes spoken audio files into text, checks the grammar of the transcribed text, and generates a grammar score using Natural Language Processing (NLP) tools.

## 🚀 Features

- ✅ Upload and transcribe audio using Google Speech Recognition
- ✅ Grammar checking using `language_tool_python`
- ✅ Grammar score based on detected issues per word
- ✅ Display of grammar issues with suggestions
- ✅ Corrected version of the transcript

---

## 🧰 Tech Stack

- Python
- Google Colab / Jupyter Notebook
- SpeechRecognition (`speech_recognition`)
- LanguageTool (`language_tool_python`)
- PyAudio (for microphone input if needed)

---

## 📦 Installation

Install dependencies using pip:

```bash
pip install SpeechRecognition
pip install PyAudio
pip install language-tool-python
```

## 📂 How to Use
Upload your audio file (WAV recommended)

Transcribe audio to text

Check grammar

View grammar score and suggestions

## 📊 Sample Output

* Transcribed text: He go to school everyday and eat a apple.
* Grammar Score: 60.00/100
* Corrected Text: He goes to school every day and eats an apple.

## 📌 Future Improvements
. Integrate Whisper for more accurate speech-to-text

. Use GPT-based scoring and correction

. Create a Streamlit or Flask UI

. Sentence-level scoring and visual error highlights

. Handle multiple languages




---

Let me know if you want a shorter version, or if you’re planning to deploy this and want to include deployment instructions (like Colab or Streamlit link).
