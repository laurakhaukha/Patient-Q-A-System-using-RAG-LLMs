# Patient-Q-A-System-using-RAG-LLMs

## Project Overview
This project explores the development and comparative evaluation of two patient question-and-answer (Q&A) systems designed to improve accessibility of health information using Natural Language Processing (NLP) methods.

The project investigates:
1) A retrieval-based TF-IDF system that retrieves the most relevant NHS documents in response to patient queries.
2)  A Retrieval-Augmented Generation (RAG) system built upon the T5-small transformer model, fine-tuned to generate concise, contextually accurate, and semantically grounded answers to
    medical questions by incorporating retrieved evidence from the TF-IDF component.

By contrasting a statistical retrieval method (TF-IDF) with a deep learning–based generative approach (RAG-T5), this proeject highlights trade-offs in explainability, accuracy, and real-world feasibility for clinical communication and patient-support systems.


## 🏥 Background
Healthcare professionals in the NHS face increasing workloads and burnout. Automating patient information retrieval through AI-driven Q&A systems offers a potential solution to reduce administrative pressure while improving patient understanding of complex medical concepts.

1) The project uses an NHS.UK dataset released as part of the OpenGPT initiative by the CogStack KCL/UCL team, containing:
2) 24,005 training and 211 test Q&A pairs
3) 2,392 full-text medical documents

Professionally validated responses with disease labels and NHS reference URLs


## 🧪 Evaluation Metrics
1) Precision, Recall, F1-score – retrieval and classification accuracy
2) ROUGE-1/2/L – n-gram overlap
3) BLEU-4 – fluency and translation-like accuracy
4) BERTScore-F1 – semantic similarity (contextual embedding comparison)

## Tools and Libraries
- Python 3.10+
- Transformers (Hugging Face)
- scikit-learn
- pandas, numpy
- torch
- matplotlib / seaborn
- nltk / spaCy

