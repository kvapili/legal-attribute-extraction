# legal-attribute-extraction
LLM-based atribute extraction pipeline for converting factual statements of court verdicts into a structured dataset

This repository provides additional material for the paper presented at the NLL2FR2025 worshop co-located at the Jurix 2025 conference.

**Legal Texts to Legal Data: LLM-Based Attribute Extraction from Court Verdicts**

*Ivana Kvapilíková, Jan Černý, Vojtěch Pour, Tomáš Knap, Klára Bendová, Jaromír Šavelka and Jakub Drápal1*

```text
legal-attribute-extraction/
├─ README.md
├─ notebooks
│  ├─ data_driven_extraction.ipynb - An iterative LLM pipeline for developing an attribute schema for attribute extraction without any expert knowledge
│  ├─ expert_based_extraction.ipynb - An LLM pipeline for extracting attributes from court verdicts given a set of pre-defined attributes including standardization
│  ├─ evaluation.ipynb - Evaluation of LLM results against human annotators
├─ data
│  ├─ categorization
│  │  ├─ DKK-dev-final.csv
│  │  ├─ DKK-test-final.csv
│  │  ├─ DKK-other-final.csv
│  ├─ attributes
│  │  ├─ dataset_DUI_attributes_1775.csv
│  ├─ evaluation
│  │  ├─ annotation_with_complete_with_curation_and_llm

```
