# VoiceAI Transcriber

VoiceAI Transcriber is a web application designed to assist healthcare professionals in transcribing speech into structured medical notes. This tool utilizes the Whisper AI model for speech recognition and allows users to create medical notes based on the transcribed content. The application runs entirely in the browser, ensuring privacy and convenience.

## Features
- **Voice Recording**: Record voice input directly from your browser using your device's microphone.
- **Real-Time Visualization**: View a visual representation of your audio input through the visualizer.
- **Speech-to-Text Transcription**: Convert recorded speech into text using the Whisper AI model.
- **LLM Integration**: Use the transcribed content to create a structured medical note with the help of a Gemini Nano Large Language Model (LLM).
- **Local Operation**: Runs locally in the browser, ensuring compliance with privacy standards.


## Restrictions and Important Information
1. **Healthcare Professional Use Only**: This tool is intended for use by licensed healthcare professionals. It is designed to assist in creating medical notes but does not replace professional medical judgment.
2. **AI Limitations**: The AI model may not always produce accurate or complete information. It can hallucinate, omit improtant information etc. Users must review and verify all transcriptions and generated notes.
3. **Privacy and Security**: Users are responsible for complying with all applicable privacy laws and regulations, such as HIPAA in the United States. Ensure that this tool can be used in your region and institution before using it.
4. **Not a Diagnostic Tool**: This tool should not be used for making medical diagnoses or treatment recommendations. It only assists with documentation.
5. **User Responsibility**: The healthcare professional is solely responsible for the accuracy and completeness of the medical notes. All AI-generated content must be reviewed and edited before incorporation into official medical records.

## Getting Started
To use the VoiceAI Transcriber:
1. Open the application in a Chrome version greater than v127 or chrome Canary.
   a. Download and install Chrome with built-in AI(Dev / Canary).
   b. Go to chrome://flags/#prompt-api-for-gemini-nano and enable the Prompt API for Gemini Nano option.
   c. Go to chrome://flags/#optimization-guide-on-device-model and turn on the Enables optimization guide on device option.
   d. Go to chrome://components/ and check or download the latest version of Optimization Guide On Device Model.
2. Click **Start Recording** to begin recording your voice input.
3. Click **Stop Recording** once you are done speaking.
4. The transcription of your speech will appear in the **Transcription** section.
5. Click **Create Medical Note** to generate a structured medical note from the transcription.

## Requirements
- Chrome version greater than v127 or chrome Canary
- Microphone access enabled
- Internet connection for downloading the Whisper model

## Disclaimer
This tool is an AI-assisted medical note creator, designed to support healthcare professionals in documenting patient encounters. It is not a substitute for professional medical judgment, and the healthcare professional remains solely responsible for all medical notes and patient care. By using this tool, users acknowledge and agree to these terms.

## License
This application utilizes the Whisper model, licensed by OpenAI. Please refer to the Whisper model license: [Whisper License](https://github.com/openai/whisper/blob/main/LICENSE)

For more information on Chrome's built-in AI features, visit: [Chrome Built-in AI](https://developer.chrome.com/docs/ai/built-in)



