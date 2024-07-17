# Dubbly

This web application allows users to dub movies from one language to another using cloned voices that mimic the original character's voice. This app identifies and separates the characters' voices, clones them, and re-attaches the new voices to the video, producing a dubbed version in the desired language.

## Features

- Extracts audio from uploaded videos
- Identifies and separates characters' voices
- Removes background music and sound effects
- Clones voices for each character
- Attaches cloned voices back to the video
- Supports dubbing in any language

## Process Flow

1. **Upload Video**: The user uploads a movie to the web app.
2. **Extract Audio**: The app extracts the audio from the video.
3. **Speaker Identification**: The app identifies and separates the characters' voices, classifying them as speaker1, speaker2, etc. It also removes background music, sound effects, and other non-dialogue audio.
4. **Voice Cloning**: The classified voices are passed to the cloned voice model for each character. Each character has a dedicated trained model.
5. **Merge Audio**: The cloned voices are attached back to the video.
6. **Final Output**: The final dubbed video is ready for download.

## Flowchart

Refer to the flowchart below for a visual representation of the process flow:

## Resources Used

- **RVC (Realistic Voice Cloning)**: For voice cloning of characters.
- **Librosa**: For audio processing tasks such as splitting, background music removal, and more.
- Other Python libraries for audio processing and machine learning tasks.

## Current Status

Due to computational constraints, only small duration videos have been tested. The project is currently in progress, and while the basic structure and output are ready, it is not yet fully complete.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/voice-cloning-movie-dubbing.git
    ```
2. Navigate to the project directory:
    ```bash
    cd voice-cloning-movie-dubbing
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the application:
    ```bash
    npm start
    ```
2. Open your web browser and navigate to `http://localhost:3000`.
3. Upload a movie file and follow the on-screen instructions to create the dubbed version.

## Contributing

Contributions are welcome! If you have any ideas or suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact [your-email@example.com](mailto:your-email@example.com).


## THE FLOW THE PROJECT
![flow chart](https://github.com/user-attachments/assets/4e3db292-e1da-4426-ba9c-4ceb97565222)

## LOGIN PAGE
![image](https://github.com/user-attachments/assets/b8d95c02-9bb0-4ff4-b30c-52683d28c3eb)

## HOME PAGE TO UPLOAD THE MOVIE
![main ui](https://github.com/user-attachments/assets/26eeeeb7-b111-4124-9cd9-daa16f5a3502)

![upload video](https://github.com/user-attachments/assets/ea8a2e0a-34b4-4289-b61d-f4db2a141947)

## FINALLY THE AUDIO GENERATED!!!
![final audio](https://github.com/user-attachments/assets/436e8500-da82-4f09-9d8a-05f0aad8522a)

## MINI AUDIO PLAYER TO PLAY THE AUDIO
![audio player](https://github.com/user-attachments/assets/ae0cf064-2253-4edf-b75d-03230a900f01)
