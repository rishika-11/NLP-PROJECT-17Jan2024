
# PLAGARISM CHECK USING NER

# Introduction
The project gives the plagarism percentage between two text and pdfs and also give the NER for the data uploaded.

# Libraries Imported:

- spacy: Used for natural language processing.
- sklearn.feature_extraction.text.TfidfVectorizer: This library is employed for TF-IDF vectorization, which is a numerical representation of the text.
- sklearn.metrics.pairwise.cosine_similarity: Utilized for computing the cosine similarity between vectors.

# Functions:

- perform_ner(text):
Input: Text as a parameter.
Process: Uses SpaCy to perform Named Entity Recognition (NER) on the provided text.
Output: Returns a list of named entities extracted from the text.

- check_plagiarism(doc1, doc2):
Input: Two documents (strings) for comparison.
Process: Converts the documents into TF-IDF matrices and calculates the cosine similarity between them.
Output: Returns the plagiarism similarity as a numeric value.

- summarize_text(text):
Input: Text as a parameter.
Process: Provides a summary of the text by extracting the first 100 characters.
Output: Returns the summarized text.

- extract_text_from_pdf(pdf_path):
Input: File path to a PDF document.
Process: Uses PyMuPDF to open the PDF, extract text from each page, and concatenate the text.
Output: Returns the extracted text from the PDF.

- Execution:
The user is prompted to input two documents (text or PDF) for plagiarism analysis.
For text input, the script performs Named Entity Recognition (NER) using SpaCy, checks plagiarism using TF-IDF and cosine similarity, and provides summaries of both documents.
For PDF input (executed in a Google Colab environment), the script allows users to upload PDFs manually. It extracts text from the PDFs, performs NER, checks plagiarism, and displays the results.

-Displayed Results:
Named Entities: Lists named entities identified in each document.
Plagiarism Similarity: Prints the similarity percentage between the two documents.
Document Summaries: Provides summaries of both documents.

- Collab Notebook link:https://colab.research.google.com/drive/1etUYPL4Rxu93AVjbj-bdWnC9_TLM0IKG?usp=sharing
