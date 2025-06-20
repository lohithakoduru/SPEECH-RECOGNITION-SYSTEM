# SPEECH-RECOGNITION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS 

*NAME* : KODURU LOHITHA

*INTERN ID* : CITS0D62 

*DOMAIN* : Artificial Intelligence

*DURATION* : 8 WEEKS

*MENTOR* : NEELA SANTOSH

** DESCRIPTION OF TASK 2:

In Task 2 of the internship, I created a basic Speech-to-Text (STT) system that automatically converts spoken words in an audio file into text. I implemented this task using Jupyter Notebook with Python kernel, leveraging the power of Python’s SpeechRecognition and pydub libraries. The goal of this task was to take an audio file (initially in .mp3 format), convert it to a .wav file, and then transcribe its content into text using Google’s speech recognition API.

The process began with audio preprocessing. Since the SpeechRecognition library works best with .wav files, I first used pydub to convert the uploaded .mp3 file to .wav. To enable this, I ensured that the system had access to an audio conversion backend (ffmpeg). Once the audio was converted, I used SpeechRecognition.Recognizer() to create a recognizer object and processed the .wav file through the recognizer. The output was a complete transcription of the spoken words in the audio file.

This tool worked well for short, clear recordings and is an example of automatic speech recognition (ASR). The converted text was displayed in the notebook output, providing a clean and accurate representation of what was spoken in the original recording.

Speech-to-text technology has numerous real-world applications. In virtual assistants like Alexa, Siri, and Google Assistant, it is used to convert voice commands into actionable text. In call centers, speech-to-text tools are used to generate call transcripts for training and quality monitoring. In education, it aids students and teachers by transcribing lectures, especially useful for note-taking or accessibility for hearing-impaired students. In media and journalism, interviews and podcasts are transcribed automatically. STT is also critical in healthcare, where doctors dictate patient reports and clinical notes for automatic transcription.

The tools used in this task included:

Python

Jupyter Notebook

SpeechRecognition – to recognize and transcribe audio

pydub – to handle audio format conversion

Google Web Speech API – used internally by the library for speech recognition

This task helped me understand the fundamentals of audio processing and introduced me to practical machine learning integration with audio input. I also learned how to handle file formats and manage compatibility issues with libraries and system tools like ffmpeg. By the end of the task, I had a working prototype that could take a voice recording, process it, and display its transcribed version in text form.

Completing this task gave me insights into building voice-enabled applications and exposed me to the challenges of audio clarity, noise handling, and speaker variation. This kind of system is highly applicable in modern AI-powered services and plays a critical role in the evolution of voice interfaces

#OUTPUT

![Image](https://github.com/user-attachments/assets/21987c14-d7bd-447c-a35a-acecfb2c2261)
