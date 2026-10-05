# 🎙️ Audio to Text (Speech-to-Text)

Convert spoken audio into text using OpenAI Whisper.

---

## 📌 Features
- Transcribes audio files into text
- Supports multiple audio formats (e.g., WAV, MP3)
- Simple Python script for quick usage
- Built with [OpenAI Whisper](https://github.com/openai/whisper)

---

## ⚙️ Installation

Clone the repository:
```bash
git clone git@github.com:swethakv18-code/audiototext.git
cd audiototext

Create a virtual environment (optional but recommended):

bash
python3 -m venv my_env
source my_env/bin/activate
Install dependencies:

bash
pip install -r requirements.txt

🚀 Usage
Run the script with your audio file:

bash
python simple_speech2text.py --file sample.wav
Example output:

Code
Transcribed text: "Hello, welcome to my speech-to-text demo."
📂 Project Structure
Code
audiototext/
├── simple_speech2text.py   # Main script
├── requirements.txt        # Dependencies
└── README.md               # Project documentation

🛠️ Requirements
Python 3.8+

torch

openai-whisper

📜 License
This project is licensed under the MIT License.



