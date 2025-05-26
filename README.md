# Named Entity Recognition using Multinomial Naive Bayes

This project implements a Named Entity Recognition (NER) system using a Multinomial Naive Bayes classifier trained on a custom labeled dataset.

## 📁 Project Structure

- `Hard_code.py`: Python script for model training and evaluation.
- `train.txt`: Training data in a token-label format.
- `README.md`: Project documentation.

## 🧾 Data Format

Each line in `train.txt` contains a word and its corresponding entity tag, e.g.:

```
John B-PER
lives O
in O
New B-LOC
York I-LOC
```

## 🔧 Features

- Token-level feature extraction
- Use of n-gram character and word-level features
- Multinomial Naive Bayes classifier from `sklearn`

## ⚙️ Requirements

- Python 3.x
- scikit-learn
- nltk
- pandas

Install with:
```bash
pip install sklearn nltk pandas
```

## 🚀 How to Run

1. Ensure `train.txt` is present in the project folder.
2. Run `Hard_code.py`:
```bash
python Hard_code.py
```

## 📈 Output

The model prints precision, recall, and F1 score, and allows you to test predictions on custom text.

## 📄 License

MIT License.
