# SPEECH-RECOGNITION-SYSTEM

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Mirza Muqaraab Ali Baig

**INTERN ID**: CT06DY2291

**DOMAIN**: Artificial Intelligence

**DURATION**: 6 WEEKS

**MENTOR**: NEELA SANTHOSH

# DESCRIPTION
This task revolves around building an intelligent system that can listen to human speech and accurately convert it into written text. In a world where voice commands, podcasts, and virtual meetings are a part of daily life, such a tool becomes invaluable. It bridges the gap between spoken communication and digital documentation, empowering accessibility and efficiency.

At the core of this project lies the Whisper model by OpenAI, specifically the Whisper Large v3 version. Whisper is a state-of-the-art automatic speech recognition (ASR) system trained on a vast and diverse dataset of multilingual audio. It is capable of understanding various accents, tones, and background noises, making it highly reliable for real-world use cases. By leveraging this advanced model, the task aims to demonstrate how artificial intelligence can interpret speech with remarkable accuracy and fluency.

The implementation uses the Transformers library from Hugging Face, a powerful toolkit that provides easy access to pre-trained models for natural language and speech processing tasks. The pipeline function is used to load the Whisper model in the “automatic-speech-recognition” mode, assigning it to the GPU for faster computation. This allows the system to process audio inputs efficiently, even for longer recordings.

The heart of the program is the transcription function. It receives an audio file—either recorded live through a microphone or uploaded from a device—and passes it to the Whisper model. The model then decodes the sound waves into textual data, producing a clear and structured transcript of the spoken words. This function ensures that spoken content is transformed into readable text seamlessly, without the need for manual transcription.

To make the tool accessible to all users, the project integrates Gradio, an intuitive Python library that allows developers to create web-based interfaces for machine learning models. The Gradio interface provides a simple, user-friendly environment where users can interact with the system effortlessly. The interface includes two primary input options—recording speech directly from a microphone or uploading an existing audio file. Once the user provides input, the system processes the audio and displays the transcribed text instantly in a clean, formatted Markdown output section.

The application is titled “Speech-to-Text”, and once launched, it runs in a web browser, providing an easy and interactive experience. The integration of GPU acceleration ensures that even large or complex audio files are processed quickly, demonstrating the real-time potential of AI-driven transcription systems.

Beyond its technical implementation, this project highlights the transformative potential of AI in communication. It can assist students in converting lectures into notes, help journalists transcribe interviews, and even enable accessibility for individuals with hearing impairments. By automating transcription, it saves time, reduces errors, and allows users to focus more on content and meaning rather than manual data entry.

In summary, this task showcases the power of combining advanced AI models like Whisper with user-friendly frameworks such as Gradio. Together, they create a bridge between human speech and digital understanding—turning voice into text with clarity, precision, and ease.
# OUTPUT
