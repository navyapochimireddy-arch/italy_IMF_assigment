Italy IMF Financial Stability Analysis

Overview

This repository contains a Python-based analysis of Italy's 2023 IMF Article IV Consultation report using Large Language Models (LLMs), structured information extraction, Retrieval-Augmented Generation (RAG) and financial visualisation.

Requirements

- Python 3
- Google Colab
- Google Gemini API key
- PyMuPDF
- Google Gen AI SDK
- Sentence Transformers
- FAISS
- Pandas, NumPy and Matplotlib

Installation

The required Python libraries are installed automatically when running the notebook's installation cells.

How to Run

1. Open "24136893.ipynb" in Google Colab.
2. Ensure "ITALY.pdf" is available at "/content/ITALY.pdf".
3. Add your Gemini API key to Colab Secrets as "GoogleGeminiAPI".
4. Run the notebook cells sequentially.
5. Review the generated results and dashboard.

Analysis Tasks

- Task 1: PDF extraction, text cleaning and LLM summarisation.
- Task 2: Thematic analysis, economic indicator extraction and JSON validation.
- Task 3: FAISS-based RAG retrieval and LLM evaluation.
- Task 4: Four-panel financial dashboard.
- Extra Credit: Multi-Query RAG benchmarking.

Outputs

Generated files are stored in "/content/italy_task1/", including:

- Cleaned report text
- Section summaries
- Economic indicators and thematic analysis JSON files
- RAG retrieval and evaluation results
- Financial dashboard (PNG)
- Multi-Query RAG comparison results

Data Source

International Monetary Fund (2023). Italy: 2023 Article IV Consultation. IMF Country Report No. 23/273.

https://doi.org/10.5089/9798400249198.002.A001

Notes

An internet connection and a valid Gemini API key are required. Model-generated findings should be verified against the original IMF report. API keys must not be published in the repository.
