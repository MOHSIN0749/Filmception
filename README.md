# 🎬 Filmception — AI Movie Summary Translator & Genre Predictor

Filmception is an AI-powered NLP application that takes in a movie summary, translates it into Urdu, Arabic, or French, reads it aloud, and predicts the movie genre using machine learning!

## 🌟 Features

- 📝 Accepts user-written movie summary
- 🌍 Translates to 3 languages: Arabic 🇸🇦, Urdu 🇵🇰, French 🇫🇷
- 🔊 Converts translation into speech (Text-to-Speech)
- 🎯 Predicts movie genres using ML classifier
- 💻 Beautiful Gradio GUI interface (Colab compatible)

## 🔧 Built With

- Python 3.11
- spaCy (NLP)
- Hugging Face Transformers (Translation)
- gTTS (Text-to-Speech)
- Scikit-learn (Genre classification)
- Gradio (Web Interface)

## 🚀 How to Use

1. Clone this repo or open the notebook in Google Colab.
2. Run the cell to install dependencies.
3. Load or train your model (joblib files provided).
4. Launch the Gradio app and interact via UI.

## 📁 Files

- filmception_gui.ipynb → Main interactive notebook (GUI app)
- genre_model.pkl → Trained multi-label genre classifier
- tfidf.pkl → TF-IDF vectorizer used for feature extraction
- label_binarizer.pkl → Label encoder for multi-label genres

## 🧠 Sample Inputs

```txt
A detective investigates a mysterious murder in a quiet town.
A group of astronauts travel through a wormhole to save humanity.
A superhero defends his city from a dangerous villain.
