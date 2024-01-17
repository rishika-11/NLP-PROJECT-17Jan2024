
# PLAGARISM CHECK USING NER

# Introduction
The project gives the plagarism percentage between two text and pdfs and also give the NER for the data uploaded.

# Dependencies
Ensure the installation of the following libraries before running the Colab notebook:

- spacy
- sklearn
- fitz
- os
- en_core_web_sm
- PyMuPDF

# Code

The integrated process of the two codes begins with user interaction, prompting input of either two text documents or two PDF files in a Colab environment. Both codes leverage SpaCy for Named Entity Recognition (NER), extracting entities from the provided documents or PDFs. Plagiarism detection is achieved through TF-IDF vectorization and cosine similarity computation, revealing the similarity between the two documents or extracted text. Additionally, a simple text summarization function condenses each document by extracting the initial 100 characters. In the second code snippet, tailored for PDF processing in Colab, the PyMuPDF library extracts text from each page of the uploaded PDFs. The display of results includes information on named entities, plagiarism similarity, and document summaries. The Colab-specific steps involve installing necessary libraries using pip and python commands, as well as manual PDF uploads using the files module in Google Colab. Collectively, these steps create a comprehensive text analysis process encompassing entity recognition, plagiarism detection, summarization, and PDF-specific functionalities.

- Collab Notebook link:https://colab.research.google.com/drive/1etUYPL4Rxu93AVjbj-bdWnC9_TLM0IKG?usp=sharing
