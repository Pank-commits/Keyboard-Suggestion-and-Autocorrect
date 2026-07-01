# Keyboard Suggestion and Autocorrect

## 📌 Overview

This project is a Python-based Keyboard Suggestion and Autocorrect system that predicts the most likely intended word when a user enters a misspelled word. The system uses Natural Language Processing (NLP) techniques and Jaccard Similarity to compare the input word with a vocabulary built from a text corpus.

The project demonstrates text preprocessing, vocabulary generation, word probability calculation, and similarity-based correction.

---

## 🚀 Features

- Text preprocessing and cleaning
- Vocabulary generation from a text corpus
- Word frequency calculation
- Probability-based word ranking
- Jaccard Similarity for autocorrect suggestions
- Suggests the closest matching word for misspelled inputs

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- TextDistance
- Regular Expressions (re)
- Jupyter Notebook

---

## 📂 Project Structure

```
Keyboard-Suggestion-and-Autocorrect/
│
├── autocorrect.ipynb      # Main notebook
├── corpus.txt             # Training text corpus
├── requirements.txt       # Required libraries
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Keyboard-Suggestion-and-Autocorrect.git
```

Move into the project directory

```bash
cd Keyboard-Suggestion-and-Autocorrect
```

Install the required packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open `autocorrect.ipynb` in Jupyter Notebook.
2. Run all the notebook cells.
3. Enter a misspelled word.
4. The model suggests the closest matching word from the vocabulary.

---

## 📊 How It Works

1. Reads the training text corpus.
2. Cleans and preprocesses the text.
3. Creates a unique vocabulary.
4. Calculates word frequencies and probabilities.
5. Computes Jaccard Similarity between the input word and vocabulary words.
6. Returns the best matching suggestion.

---

## 📈 Future Improvements

- Implement Levenshtein Distance
- Add Edit Distance-based correction
- Build a GUI using Streamlit
- Support real-time typing suggestions
- Integrate machine learning models for improved accuracy

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.
