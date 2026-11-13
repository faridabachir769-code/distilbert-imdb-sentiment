# DistilBERT sentiment analysis (IMDB)

Fine-tuning of `distilbert-base-uncased` on a subset of the IMDB movie
reviews dataset, trained on Kaggle (T4 GPU).

- **Task:** binary sentiment classification (POSITIVE / NEGATIVE)
- **Training data:** 5,000 reviews; evaluation on 1,000 reviews
- **Result:** ~87.8% accuracy (first run, check against your latest run)
- **Model:** https://huggingface.co/Farvel28/distilbert-imdb-sentiment

## Files
- `distilbert-imdb-sentiment.ipynb`: training and evaluation code
