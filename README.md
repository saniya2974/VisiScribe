# VisiScribe

VisiScribe is an AI-driven assistive system designed to enhance accessibility for visually impaired and elderly individuals. It generates real-time image captions using advanced computer vision and natural language models, converts them to speech for auditory assistance, and performs sentiment analysis to provide emotional context.
Trained on Flickr8k and Amazon Customer Review dataset, for understanding different patterns of image and understanding sentiments from reviews respt.
# Key Features
 1. Real-time Captioning: Uses the BLIP model to generate descriptive captions from both real-time camera feeds and uploaded images.

 2. Text-to-Speech (TTS): Converts generated captions into natural-sounding audio to assist users with visual impairments.

 3. Sentiment Analysis: Analyzes the emotional tone of the generated captions using Sentence Transformers and XGBoost.

 4. Modular Design: Built with a scalable architecture to easily integrate into broader assistive technology solutions.

# Technologies Used:

Python
OpenCV
BLIP (Bootstrapped Language Image Pretraining)
Text-to-Speech Engines
XGBoost
Sentence Transformers
