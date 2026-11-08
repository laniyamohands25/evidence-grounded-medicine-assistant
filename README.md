# evidence-grounded-medicine-assistant
An evidence-grounded Generative AI application that identifies active and inactive medicine ingredients and explains their purposes and safety considerations using pretrained LLMs and Retrieval-Augmented Generation.
# Evidence-Grounded Generative AI Assistant for Understanding Medicine Ingredients and Safety Information

An evidence-grounded Generative AI application that identifies active and inactive ingredients in medicines and explains their purposes and relevant safety information using reliable pharmaceutical sources and Retrieval-Augmented Generation (RAG).

## Project Overview

Medicine labels contain technical information about active pharmaceutical ingredients (APIs) and inactive ingredients (excipients). Understanding their functions and relevant safety considerations can be challenging for non-expert users.

This project aims to develop an accessible Generative AI assistant that retrieves information from reliable pharmaceutical sources and generates understandable, evidence-supported explanations.

The system is intended for educational and informational purposes. It does not diagnose medical conditions or replace professional medical advice.

## Problem Statement

Existing medicine information resources can be difficult for non-experts to interpret. General-purpose AI systems may also generate incomplete, outdated, or unsupported information.

An evidence-grounded approach is needed to identify medicine ingredients, retrieve relevant information, and generate explanations supported by reliable sources.

## Aim

To develop an evidence-grounded Generative AI assistant that identifies active and inactive medicine ingredients and provides understandable explanations of their purposes and relevant safety considerations.

## Objectives

- Identify active and inactive ingredients from medicine labels.
- Retrieve ingredient-related information from reliable pharmaceutical sources.
- Use pretrained and fine-tuned language models to generate understandable explanations.
- Provide evidence and references supporting generated information.
- Reduce unsupported responses through Retrieval-Augmented Generation.
- Evaluate ingredient identification accuracy, factuality, readability, and explanation quality.

## Proposed Methodology

1. **Medicine Input:** Accept a medicine name or medicine label.
2. **Ingredient Identification:** Extract and classify active ingredients and inactive ingredients.
3. **Information Retrieval:** Retrieve relevant information from reliable pharmaceutical and drug-label databases.
4. **Knowledge Processing:** Organize retrieved information for evidence-based response generation.
5. **Generative AI:** Use a pretrained language model with RAG to produce understandable explanations.
6. **Evidence Presentation:** Display ingredient information, safety considerations, and supporting sources.
7. **Evaluation:** Assess ingredient identification, retrieval quality, factual accuracy, and readability.

## Technology Stack

*To be finalized during implementation.*

- Python
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Sentence Transformers
- Vector Database
- Streamlit
- Pharmaceutical and drug-label databases

## Project Structure

```text
evidence-grounded-medicine-assistant/
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample_data/
├── notebooks/
├── src/
├── app/
├── evaluation/
├── docs/
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Evaluation

The proposed system will be evaluated using:

- Ingredient identification accuracy
- Precision, recall, and F1-score
- Retrieval quality
- Factual accuracy and evidence support
- Citation correctness
- Readability and explanation quality

## Team

- Laniya Mohan
- Project Team Member 2

## Disclaimer

This application is designed for educational and informational purposes only. It does not provide medical diagnoses, prescribe treatments, or determine whether a medicine is universally safe or unsafe. Users should consult qualified healthcare professionals for medical decisions.
