# 🎬✨ Dubbly
**The Movie Dubbing App 🎭🎶**

This web application allows users to dub movies from one language to another using cloned voices that mimic the original character's voice. This app identifies and separates the characters' voices, clones them, and re-attaches the new voices to the video, producing a dubbed version in the desired language.

## Features

- 🎥 Extracts audio from uploaded videos
- 🎭 Identifies and separates characters' voices
- 🎶 Removes background music and sound effects
- 🗣️ Clones voices for each character
- 📼 Attaches cloned voices back to the video
- 🌐 Supports dubbing in any language



## Flowchart

Refer to the flowchart below for a visual representation of the process flow:
![flow chart](https://github.com/user-attachments/assets/4e3db292-e1da-4426-ba9c-4ceb97565222)


## Resources Used

- **RVC (Retrieval-Based Voice Conversion)**: For voice cloning of characters.
  RVC stands for Retrieval-Based Voice Conversion, a novel approach in the field of AI voice models. Unlike traditional methods, RVC utilizes advanced algorithms 
  to clone voices with remarkable accuracy. This technology has been pivotal in developing realistic AI cover voices and voice generators.
  
- **Librosa**: For audio processing tasks such as splitting, background music removal, and more.
- **Spleeter**: An open-source library by Deezer that performs source separation, which can separate vocals from music tracks.
- **PyDub**: Great for simple audio manipulations such as splitting and merging audio files.
- Other Python libraries for audio processing and machine learning tasks.

## Current Status

Due to computational constraints, only small duration videos have been tested. The project is currently in progress, and while the basic structure and output are ready, it is not yet fully complete.


## Process Flow

1. **Upload Video**: The user uploads a movie to the web app.
2. **Extract Audio**: The app extracts the audio from the video.
3. **Speaker Identification**: The app identifies and separates the characters' voices, classifying them as speaker1, speaker2, etc. It also removes background music, sound effects, and other non-dialogue audio.
4. **Voice Cloning**: The classified voices are passed to the cloned voice model for each character. Each character has a dedicated trained model.
5. **Merge Audio**: The cloned voices are attached back to the video.
6. **Final Output**: The final dubbed video is ready for download.

   

## LOGIN PAGE
![image](https://github.com/user-attachments/assets/b8d95c02-9bb0-4ff4-b30c-52683d28c3eb)


## HOME PAGE TO UPLOAD THE MOVIE
![main ui](https://github.com/user-attachments/assets/26eeeeb7-b111-4124-9cd9-daa16f5a3502)


## PREVIEW OF THE MOVIE
![upload video](https://github.com/user-attachments/assets/ea8a2e0a-34b4-4289-b61d-f4db2a141947)


## FINALLY THE AUDIO GENERATED!!!
![final audio](https://github.com/user-attachments/assets/436e8500-da82-4f09-9d8a-05f0aad8522a)


## MINI AUDIO PLAYER TO PLAY THE AUDIO
![audio player](https://github.com/user-attachments/assets/ae0cf064-2253-4edf-b75d-03230a900f01)


## Also tried to generate a commentry for the football match using cloned voice.

![football1](https://github.com/user-attachments/assets/15d14e72-78f4-4c2f-a280-8700c73772da)


## SAMPLE CLONINGS
**Cloned RJ Balaji's voice and tried with different dialogues**:

Original Dialogue : https://drive.google.com/file/d/1wwpfDHmKfiEBtv0vdOPTOJLzjhDxVsgu/view?usp=sharing
Cloned Dialogue   : https://drive.google.com/file/d/1hcnSQByOVSSNeAr9MOJD5eZMcVkgiRZb/view?usp=sharing
