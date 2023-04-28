# File-Similarity-Checker
Text Similarity Comparison Tool The Text Similarity Comparison Tool is a Python utility that allows you to compare the similarity between two text documents. Whether you need to check for plagiarism, compare document versions, or analyze textual similarities, this tool provides an easy and efficient solution.

Features:
File Format Support: The tool supports both DOCX and PDF file formats, making it versatile for various document types.

Text Pre-processing: It performs essential text pre-processing tasks, including lowercasing, punctuation removal, tokenization, stopword removal, and lemmatization.

Similarity Highlighting: The tool highlights similarities between the texts, visually emphasizing shared words or phrases.

Repeated Word Count: It counts the occurrence of repeated words in both files and provides a detailed report.

TF-IDF and Cosine Similarity: The tool utilizes TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity measures to calculate the similarity percentage between texts.

Command Line Interface: The tool provides a command-line interface, making it user-friendly and easy to integrate into workflows.

Usage:
Clone or download the repository to your local machine.
Install the required dependencies listed in the requirements.txt file.
Run the similarity.py script.
Enter the paths of the two files (DOCX or PDF) you want to compare.
The tool will analyze the texts, highlight similarities, and provide a similarity percentage.
It will also display a report of repeated words with their respective counts.


Dependencies:
Python
fitz (PyMuPDF)
docx
nltk
string
scikit-learn
