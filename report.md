# Byte Pair Encoding (BPE) Tokenizer Report

## Introduction

Byte Pair Encoding (BPE) is a subword tokenization algorithm widely used in Natural Language Processing (NLP). It reduces the vocabulary size by repeatedly merging the most frequent adjacent character pairs. Modern Large Language Models (LLMs) such as GPT, BERT, and RoBERTa use BPE or similar tokenization techniques.

---

## Objective

- Implement the BPE algorithm from scratch.
- Learn merge rules from a text corpus.
- Generate a subword vocabulary.
- Encode and decode words using learned tokens.

---

## Algorithm

1. Read the corpus.
2. Convert text to lowercase.
3. Split words into characters.
4. Append the `</w>` end-of-word symbol.
5. Count word frequencies.
6. Find adjacent symbol pairs.
7. Count pair frequencies.
8. Merge the most frequent pair.
9. Update the vocabulary.
10. Repeat until the desired number of merges is reached.
11. Store merge rules.
12. Build the final vocabulary.
13. Encode and decode words.

---

## Advantages

- Reduces vocabulary size.
- Handles unknown words efficiently.
- Improves tokenization accuracy.
- Widely used in NLP applications.

---

## Applications

- Large Language Models (LLMs)
- Machine Translation
- Chatbots
- Text Classification
- Text Generation
- Search Engines

---

## Conclusion

This project successfully implements the Byte Pair Encoding (BPE) algorithm from scratch using Python. It demonstrates vocabulary learning, merge rule generation, and word encoding/decoding, providing a strong foundation for understanding tokenization in modern AI systems.

---

## Author

**Sibiral Ruban**

