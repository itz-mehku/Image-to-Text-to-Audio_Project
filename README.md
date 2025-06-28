# Image-to-Text-to-Audio_Project
## Mini Project 10 : Image to Text to Audio
## * Project Overview
--> This program demonstrates a simple pipeline that **extracts text from an image** and **converts it into speech**. It uses **Tesseract OCR** to recognize text from the image and **Google Text-to-Speech (gTTS)** to generate audio from the extracted text.

## * Technologies Used
- Python

- Tesseract OCR

- pytesseract – Python wrapper for Tesseract

- Pillow (PIL) – For image processing

- gTTS (Google Text-to-Speech) – For converting text to audio

- IPython.display.Audio – To play the audio in Google Colab

## * How It Works
1. Image Upload: The user loads an image containing text.

2. Text Extraction: Tesseract OCR reads the text from the image.

3. Text-to-Speech Conversion: The extracted text is converted to speech using gTTS.

4. Audio Playback: The resulting audio is saved as an MP3 file and played in the notebook.

## * How to Run
1. Upload your image (e.g., `Picture1.png`) to the Colab environment.

2. Run the notebook cells step by step.

3. The program will:

   - Print the extracted text.

   - Generate and save an audio file.

   - Play the audio in the notebook.
