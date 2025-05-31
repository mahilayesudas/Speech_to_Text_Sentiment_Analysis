# Speech_to_Text_Sentiment_Analysis

This project demonstrates how to use Google Cloud Platform (GCP) APIs to convert speech into text and analyze the sentiment of each spoken sentence. It simulates a real-world call center transcription and insight extraction pipeline.

**Technologies Used**

  -> Google Cloud Speech-to-Text API for transcription
  
  -> Google Cloud Natural Language API for sentiment analysis
  
  -> Google Cloud Firestore for storing results
  
  -> Python 

**What This Notebook Does**

-> Transcribes Audio Files: Converts .wav audio files stored in a GCP bucket into readable text using GCP's Speech-to-Text API.

-> Analyzes Sentiment: Uses GCP's Natural Language API to evaluate the sentiment (positive/negative) and emotional intensity (magnitude) of each sentence.

-> Stores Insights: Saves each sentence’s transcription, sentiment score, and metadata (e.g., file name, timestamp) to Firestore.

**Key Insights**

-> Mixed Emotions: The conversation includes both highly positive (score ~0.9) and negative (score ~-0.7) sentiments—suggesting both satisfaction and frustration.

-> Emotional Intensity: Strong sentiments correlate with high emotional intensity (magnitude), pinpointing emotionally charged interactions.

-> Tone Fluctuation: The sentiment varies sentence by sentence, reflecting changing emotions during the customer interaction.

-> Overall Outcome: Despite some negative moments, positive sentiment dominates—indicating a generally satisfactory customer experience.
