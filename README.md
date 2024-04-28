# speech-to-text-transcription-nlp-model-for-indian-regional-languages
# Indian Multilingual Speech-to-Text Transcription

## Description
In a multilingual and diverse linguistic landscape like India, bridging the gap between spoken language and written text is of paramount importance. Our solution contributes significantly to breaking language barriers, fostering inclusivity, and enabling wider access to information in India. It empowers individuals and organizations to convert spoken content in multiple Indian languages, including various accents and dialects, into text, facilitating communication, education, and information dissemination.

## Solution Overview
- The prototype model utilizes the XLSR-Wav2Vec2 model from Hugging Face.
- Fine-tuned the model according to our preferred languages to achieve accurate results.
- Utilizes the Connectionist Temporal Classification (CTC) algorithm for speech recognition and accent purposes.
- Data preprocessing involved converting audio files as per model requirements, creating a specialized token vocabulary, and selecting a model capable of recognizing 39 unique letters at once.
- Achieved high accuracy measured by the word error rate (WER), with around 80% accuracy for Indian English.
- For translation to English, we employed the Googletrans module.
- Customized Wav2Vec2 for Indian linguistic diversity, ensuring accurate, accessible, and multilingual speech-to-text transcription.

## Features
- Real-time transcription and translation.
- Focus on Indian languages, accents, and native scripts.
- Adaptability and versatility demonstrated through fine-tuning and integration of accent symbols in the dataset.

## Applications
- Education sector
- Content creation
- Effective communication in India's multilingual society

## License
All Rights Reserved

## Acknowledgements
I would like to express my gratitude to the team members and mentor for their invaluable contributions to this project
