# RAGAS Evaluation

RAG evaluation helps assess whether a RAG system generates answers that are grounded in retrieved information, relevant to the question, and supported by sufficient context.

This project evaluates a Retrieval-Augmented Generation (RAG) pipeline using RAGAS and examines how its evaluation scores reflect system performance.

## Evaluation

The project covers four metrics:

- **Faithfulness**
- **Answer Relevancy**
- **Context Precision**
- **Context Recall**

Together, these metrics assess answer quality and the relevance and coverage of retrieved context.

## Experiments

The notebook includes baseline evaluation, question-level score analysis, identification of the weakest examples, and a comparison between normal retrieval and intentionally degraded retrieval using randomly selected documents.
