# NLP-Inspector
NLP-Inspector is a Web Application capable of generating a network graph extracting entities from corpora, using `spaCy`'s [Named Entity Recognition](https://spacy.io/usage/linguistic-features#:~:text=A%20named%20entity,your%20use%20case.) (NER).

## The repository consists of
A Python API that:
- Implements basic CRUD operations.
- Creates corpora from user upload.
- Accepts plain text, PDF and Microsoft Word files.
- Builds a network graph data structure from the extracted entities.
- Provides the graph data structure to the user interface.

A user interface which allows user to:
    - Upload a corpus (large folder or URL)
