# Audio Transcription and Summarization with Whisper and OpenAI

## Description
This program is a tool for automatically transcribing and summarizing the content of audio and video files. It uses Whisper's voice recognition technology for transcription and OpenAI's API for generating summaries. It is designed to be run in a Google Colab environment.

## Features
- **Audio/Video Transcription**: Uses the Whisper model to transcribe audio extracted from video files.
- **Automatic Language Detection**: Ability to detect the language of the audio for accurate transcription.
- **Summary Generation**: Uses the OpenAI API to summarize the transcribed text, ideal for meetings, conferences, etc.

## Use of the OpenAI API
This program makes use of the OpenAI API, which is a paid service. Please **use this API responsibly** to avoid excessive charges.

## GPU Configuration
It's crucial to ensure that you are using a GPU in Google Colab for optimal performance. To activate the GPU:
   - Go to `Runtime` > `Change runtime type`.
   - Select `T4 GPU` in the hardware accelerator option.
   - Save and proceed to run the notebook.

## Usage Instructions
1. **Video Upload**: Upload your video file to the Colab environment.
2. **Video Configuration**: Update the path in the script to match the location of your uploaded video.
3. **API Configuration**: Verify that the OpenAI API key is correctly configured in the environment.
4. **Script Execution**: Go to `Runtime` > `Run all`.
5. **Access to Results**: The transcribed and summarized texts will automatically be saved in text files within the Colab environment.

## Dependencies
- **Whisper**: Advanced voice recognition.
- **moviepy**: Video editing and processing.
- **ffmpeg**: Conversion and manipulation of multimedia files.
- **tiktoken**: Authentication token management.
- **openai**: Interface for OpenAI language models (GPT-3-5 in this case).

## Authors and Acknowledgments
This script has been developed by Alejandro Oliveros Ordás with the help of OpenAI and Whisper technologies.
