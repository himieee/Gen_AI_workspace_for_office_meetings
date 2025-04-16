# TARP Final Project

This repository contains the Jupyter Notebook implementation of our TARP project. The project leverages audio/video processing, speech transcription, language translation, and vector-based similarity search using large language models.



## Overview

The notebook performs the following tasks:
- Installs required packages for transcription, translation, and NLP.
- Processes audio or video files to extract speech.
- Transcribes spoken content using OpenAI Whisper/WhisperX.
- Translates the transcribed text using deep translators.
- Uses language models and vector stores (e.g., FAISS) for contextual understanding and query processing.

## Requirements

The notebook requires the following Python packages (installed within the notebook):
- `openai-whisper`
- `whisperx`
- `pydub`
- `moviepy`
- `langchain`
- `faiss-cpu`
- `tiktoken`
- `sentence-transformers`
- `deep_translator`
- `nltk`
- `pandas==2.2.2`

## How to Run

1. Open the notebook: `tarp_final (3).ipynb`
2. Run all cells sequentially in a Jupyter environment with internet access.
3. Ensure necessary audio/video files are in the correct path if required by the script.

## Notes

- The notebook assumes the availability of required API keys (e.g., OpenAI) for some components.
- Some steps may require additional NLTK downloads (handled within the notebook).

---

