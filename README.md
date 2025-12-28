# Phraseology Extraction Module (French)

## Overview

This module is part of the **onto-phraseology** project and focuses on the
automatic extraction of phraseological units from **French corpora**.

It relies on **spaCy-based linguistic processing** to identify candidate
multi-word expressions and phraseological patterns, serving as a preliminary
step for subsequent **ontological modeling of phraseology**.

---

## Objectives

- Automatically process large French textual corpora
- Identify candidate phraseological units (MWEs, idiomatic patterns)
- Prepare structured outputs for ontological representation
- Bridge corpus-based extraction and phraseological ontology construction

---

## Methodology

The pipeline implemented in this module includes:

1. Corpus loading from plain text files
2. Linguistic preprocessing with spaCy (tokenization, POS tagging, dependency parsing)
3. Pattern-based and heuristic extraction of phraseological candidates
4. Iterative refinement and filtering
5. Preparation of data for downstream ontological modeling

---

## Repository Contents

- `phraseology_extraction_fr_spacy.ipynb`  
  Main Jupyter notebook implementing the extraction pipeline

- `sample_data/`  
  Small sample corpus provided for demonstration and reproducibility

- `requirements.txt`  
  Python dependencies required to run the notebook

---

## Installation

Create a virtual environment (recommended), then install dependencies:

```bash
pip install -r requirements.txt
```
Download the French spaCy model:
```
python -m spacy download fr_core_news_sm
```

---
## Usage

Open the notebook and run the cells sequentially:

```
jupyter notebook phraseology_extraction_fr_spacy.ipynb
```
The notebook is compatible with Google Colab and local Jupyter environments.

## Notes on Data

Due to copyright and ethical constraints, full corpora are not distributed.
Only small sample files are provided for illustration purposes.

## Position within the Project

This module provides the corpus-driven foundation for the
onto-phraseology project:

    extraction → conceptualization → ontological modeling

    language data → phraseological units → semantic relations

## Author

Lian CHEN 陈恋
CRLAO (CNRS – INALCO) & LLL (University of Orléans)
