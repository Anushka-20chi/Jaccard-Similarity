# Spelling Correction Using Jaccard Similarity

## 📖 Overview
This project implements a simple spell correction system using the **Jaccard Similarity** algorithm. It compares misspelled words with a predefined dictionary and suggests the closest matching word based on character-level similarity.

The project demonstrates how text similarity techniques can be applied in Natural Language Processing (NLP) for spelling correction.

---

## 🚀 Features
- Detects misspelled words
- Uses Jaccard Similarity for word comparison
- Suggests the most similar correct word
- Calculates similarity scores
- Simple and easy-to-understand implementation in Python

---

## 🛠️ Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy

---

## 📂 Project Structure

```
Spelling-Correction-Using-Jaccard-Similarity/
│
├── Spelling Correction Using Jaccard Similarity.ipynb
├── README.md
└── dataset (if applicable)
```

---

## ⚙️ How It Works

1. Load the dictionary of correct words.
2. Input a misspelled word.
3. Convert words into character sets.
4. Compute the Jaccard Similarity between the input word and every dictionary word.
5. Return the word with the highest similarity score as the suggested correction.

---

## 📊 Example

| Misspelled Word | Suggested Word |
|-----------------|----------------|
| computr         | computer       |
| progrmming      | programming    |
| pyhton          | python         |

---

## ▶️ How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run all cells.
4. Enter a misspelled word to receive the suggested correction.

---

## 📚 Learning Outcomes

- Text preprocessing
- Set operations in Python
- Jaccard Similarity
- Basic Natural Language Processing (NLP)
- Spell correction technique
  
