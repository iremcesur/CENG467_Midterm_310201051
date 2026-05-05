# CENG 467 Take-Home Midterm

**Student:** Irem Cesur (310201051)
**Course:** CENG 467 - Natural Language Understanding and Generation
**Instructor:** Prof. Dr. Aytug Onan

## Project Structure

- `q1_classification/` - Text classification (IMDb)
- `q2_ner/` - Named Entity Recognition (CoNLL-2003)
- `q3_summarization/` - Text summarization (CNN/DailyMail)
- `q4_translation/` - Machine translation (Multi30k)
- `q5_language_modeling/` - Language modeling (WikiText-2)
- `utils/` - Shared utilities (seed, metrics, logging)
- `report/` - LaTeX report and figures

## Reproducibility

All experiments use fixed random seeds (seed=42).

## Setup

```bash
pip install -r requirements.txt
```

## Notebooks

Each question has its own notebook(s) under `q*/notebooks/`. Run on Google Colab with GPU (T4) for transformer models.
