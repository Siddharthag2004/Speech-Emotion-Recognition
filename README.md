# Speech Emotion Recognition
## Introduction
* Speech emotion recognition (SER) is the field of technology focused on identifying the emotional state of a speaker from their voice. This goes beyond the words spoken and analyzes how they are spoken.
* The idea behind creating this project was to build a machine-learning model that could detect emotions from the speech we have with each other all the time. Nowadays personalization is something that is needed in all the things we experience every day.
* So why not have an emotion detector that will gauge your emotions and in the future recommend you different things based on your mood This can be used by multiple industries to offer different services like marketing companies suggesting you buy products based on your emotions, the automotive industry can detect the person emotions and adjust the speed of autonomous cars as required to avoid any collisions etc.
## Methodology
* Speech Input: Similar to standard speech recognition, the user's voice is recorded.
* Dataset Used: Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess).
* Pre-processing: The audio is prepared by removing noise and potentially isolating specific speech segments.
* Data augmentation: Audio includes injecting noise, stretching, shifting, and adjusting pitch to diversify training data, enhancing model robustness and performance.
* Feature Extraction: Crucial features related to emotions are extracted.
* Emotion Model: A trained machine learning model (often using classification algorithms) takes these features and identifies the associated emotion.
* Emotion Output: The system outputs the detected emotion, typically with probability or confidence scores (e.g., angry, happy, sad, neutral, etc.).
