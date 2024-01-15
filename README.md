<div align="center">
  
![VoiceIt](https://i.imgur.com/DendqCA.png)
  
<a href="https://github.com/ImPavloh/VoiceIt" target="_blank"><img src="https://img.shields.io/github/license/impavloh/voiceit?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://twitter.com/ImPavloh" target="_blank"><img src="https://img.shields.io/badge/Follow-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white"></a>
<a href="https://voiceit.pavloh.com" target="_blank"><img alt="Online use" src="https://img.shields.io/badge/WEBSITE-401769?style=for-the-badge&logo=react&logoColor=white"></a>
<a href="https://huggingface.co/spaces/ImPavloh/voiceit/tree/main" target="_blank"><img src="https://img.shields.io/badge/HuggingFace-%23E06011.svg?style=for-the-badge"></a>

<p><strong>README Language</strong></p>
<a href="README.md"><img alt="English" src="https://unpkg.com/language-icons/icons/en.svg" width="50px" style="border-top-left-radius: 25px; border-bottom-left-radius: 25px;"></a>
<a href="README_es.md"><img alt="Spanish" src="https://unpkg.com/language-icons/icons/es.svg" width="50px"></a>

</div>

# 🎙️ VoiceIt!

This project uses pre-trained models to change the voice in audio files. The service allows you to upload audio files, select a voice model, and generate a new audio file with the modified voice.

# 📚 Relevant Information 🚀

You can use VoiceIt directly online on my website **https://voiceit.pavloh.com** or use your resources and host the project locally by following the steps below.

### Requirements

- Python >3.7
- Gradio
- FFmpeg
- FFprobe

### 🛠️ Installation

1. Clone the repository:
`git clone https://github.com/impavloh/voiceit.git`

2. Change to the project directory:
`cd voiceit`

3. Install the necessary dependencies:
`pip install -r requirements.txt`

4. Create a folder called "models" and import pre-trained models to use later. In this case, you can use my models: 
https://huggingface.co/ImPavloh/Streamers-AI-Voices

5. Run the main script:
`python voiceit.py`

### 📝 Usage

1. When running the voiceit.py file, a terminal will open with a link to access the VoiceIt! interface. For example: `http://localhost:7860`

2. Select a voice model from the dropdown list.

3. Upload an audio file.

4. Click on the "Change voice" button to generate a new audio file with the modified voice.

5. Listen or download the result in the audio player.

6. You can delete the data and restart the process using the "Delete" button.

## ⚠️ Warning

- Audio files should contain only one voice and be free of noise or background music.
- The conversion time will depend on the duration of the audio and web usage (if used locally it will depend on your resources)

## 📝 License and Terms of Use

> By using this project, you agree to the [license](https://raw.githubusercontent.com/ImPavloh/VoiceIt/main/LICENSE) and [terms of use](https://raw.githubusercontent.com/ImPavloh/VoiceIt/main/TERMINOS_DE_USO.txt).
