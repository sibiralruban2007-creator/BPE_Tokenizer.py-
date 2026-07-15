# Custom Byte Pair Encoding (BPE) Tokenizer from Scratch

## Project Overview

This project implements a **Byte Pair Encoding (BPE) Tokenizer** from scratch using Python. BPE is a subword tokenization algorithm widely used in Natural Language Processing (NLP) and Large Language Models (LLMs) such as GPT, BERT, and RoBERTa. The tokenizer learns the most frequent symbol pairs and merges them iteratively to build a subword vocabulary.

---

## Objectives

* Implement the Byte Pair Encoding (BPE) algorithm from scratch.
* Learn merge rules from a text corpus.
* Generate a subword vocabulary.
* Encode words into subword tokens.
* Decode tokens back into the original words.

---

## Features

* Corpus creation and preprocessing
* Character-level tokenization
* Pair frequency calculation
* Most frequent pair selection
* Pair merging
* Merge rule learning
* Final vocabulary generation
* Token ID creation
* Encoding and decoding functions
* Sample test outputs

---

## Project Structure

```
BPE-Tokenizer/
│── BPE_Tokenizer.py
│── corpus.txt
│── README.md
│── LICENSE
│── GDPR.md
│── requirements.txt
│── .gitignore
└── screenshots/
```

---

## Algorithm

1. Create a text corpus.
2. Read the corpus.
3. Convert all words to lowercase.
4. Split each word into characters.
5. Append the end-of-word symbol (`</w>`).
6. Count word frequencies.
7. Find adjacent symbol pairs.
8. Count pair frequencies.
9. Select the most frequent pair.
10. Merge the pair into a new token.
11. Update the vocabulary.
12. Repeat the merge process.
13. Store merge rules.
14. Build the final vocabulary.
15. Encode new words.
16. Decode tokens back into words.

---

## Requirements

* Python 3.x

Libraries used:

* collections
* re

---

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Run:

```bash
python BPE_Tokenizer.py
```

---

## Sample Output

```
Encoded : ['t', 'o', 'k', 'en', 'i', 'z', 'a', 'tion</w>']
Decoded : tokenization

Encoded : ['m', 'a', 'ch', 'i', 'n', 'e</w>']
Decoded : machine
```

---

## Applications

* Natural Language Processing (NLP)
* Large Language Models (LLMs)
* Machine Translation
* Text Generation
* Chatbots
* Search Engines
* Information Retrieval

---

## Author

**Sibiral Ruban**

---

