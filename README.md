# TensorFlowTTS-data-annotation
### About The Project
At Zedni, we are pioneering the development of a state-of-the-art text-to-speech (TTS) model focused on generating natural-sounding speech in Arabic. Utilizing the powerful TensorflowTTS framework and a meticulously curated dataset from popular Saudi Arabian YouTube channels, our model is designed to perform in diverse acoustic environments. This project encapsulates our journey from data collection through model training, including the challenges we faced with audio quality and speaker variability, and our innovative solutions to these challenges.

# Built With
TensorflowTTS
Python
YouTubeTranscriptApi
WhisperModel
Gradio
Getting Started
To get a local copy up and running, follow these simple steps.

## Prerequisites
This project requires Python 3.8+ and pip. It's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate
````

# Installation
Clone the repo
```bash
git clone https://github.com/your_username_/TensorFlowTTS-data-annotation.git
````
Install required packages
```bash

pip install -r requirements.txt
````
# Usage
This project is divided into several stages, each corresponding to a script provided in the scripts folder. Below is a brief overview of each stage:

* 1 - Data Collection: Utilize the YouTubeTranscriptApi to fetch and save transcripts as JSON files.
* 2 - Individual Transcription Extraction: Process the JSON files to extract individual transcriptions into text files.
* 3 - Merge Transcriptions: Combine all individual transcription text files into a single file for processing.
* 4 - Whisper Transcription and Segmentation Pipeline: Use the WhisperModel to transcribe and segment the audio files for training.
* 5 - Arabic Text Similarity Analysis: Analyze the text data for similarity to refine the dataset.
* 6 - Gradio Interface for Manual Revision: Utilize Gradio to manually review and edit the transcriptions.

## Please refer to the corresponding script in the scripts folder for detailed usage instructions for each stage.

### Acknowledgments
* TensorflowTTS
* YouTubeTranscriptApi
* WhisperModel
* Gradio
