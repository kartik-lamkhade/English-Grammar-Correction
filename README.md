# Grammar Correction Model

This repository contains a simple **Grammar Correction Model** designed to take grammatically incorrect English sentences as input and output their corrected versions. The project is intended for learning, experimentation, and evaluation of NLP models such as **Transformer / T5-based models**.

---

## 📌 Project Overview

The goal of this project is to build and test a model that:

* Accepts an incorrect English sentence
* Corrects grammatical errors (tense, subject-verb agreement, plurality, articles, etc.)
* Outputs a grammatically correct sentence

Example:

```
Input : i has a pen
Output: I have a pen.
```

---

## 🧪 Test Sentences

The model is evaluated using manually created test sentences.

### Easy Examples

| Input                     | Output                        |
| ------------------------- | ----------------------------- |
| she go to school everyday | She goes to school every day. |
| i has two brother         | I have two brothers.          |
| he don’t like coffee      | He doesn’t like coffee.       |

### Medium Examples

| Input                                 | Output                                      |
| ------------------------------------- | ------------------------------------------- |
| she did not went to college yesterday | She did not go to college yesterday.        |
| i am learning english from two year   | I have been learning English for two years. |

### Failure Check Examples

| Input                         | Output                       |
| ----------------------------- | ---------------------------- |
| this are my notebook          | These are my notebooks.      |
| he was very happily yesterday | He was very happy yesterday. |

---

## 🧠 Model Details

* Model Type: Transformer / T5 (Text-to-Text)
* Task: Grammar Correction
* Input Format:

```
grammar: <incorrect sentence>
```

* Output Format:

```
<corrected sentence>
```

---

## ⚙️ How to Test the Model

1. Load the trained model and tokenizer
2. Pass an incorrect sentence as input
3. Generate the corrected output

Example:

```
Input : i am agree with you
Output: I agree with you.
```

---

## 📊 Evaluation

* Loss calculation is optional during testing
* BLEU score or exact-match accuracy can be used
* Manual inspection is recommended for small test sets

---

## 🚀 Future Improvements

* Train on larger parallel datasets
* Handle punctuation and capitalization better
* Improve semantic correctness
* Add web or Android app interface

---

## 👤 Author

**Kartik Lamkhade**
Learning-focused NLP & Deep Learning Enthusiast

---

## 📄 License

This project is for educational and research purp
