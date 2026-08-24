# Waltsoft AWS Marketplace — SageMaker Sample Notebooks

Sample notebooks for deploying Waltsoft machine learning products from AWS
Marketplace as Amazon SageMaker endpoints.

Each notebook is self-contained: subscribe to the product in AWS Marketplace, paste
the model package ARN shown for your Region, then run the cells top to bottom.

## Wave 1 — Embeddings, Reranking & Specialized NLP

| Product | Notebook | Task |
|---|---|---|
| BGE Large EN v1.5 | [`notebooks/bge-large-en-v1-5.ipynb`](notebooks/bge-large-en-v1-5.ipynb) | Text embeddings (feature extraction) |
| BGE Base EN v1.5 | [`notebooks/bge-base-en-v1-5.ipynb`](notebooks/bge-base-en-v1-5.ipynb) | Text embeddings (feature extraction) |
| BGE Small EN v1.5 | [`notebooks/bge-small-en-v1-5.ipynb`](notebooks/bge-small-en-v1-5.ipynb) | Text embeddings (feature extraction) |
| Prompt Injection Detector v2 | [`notebooks/deberta-v3-prompt-injection-v2.ipynb`](notebooks/deberta-v3-prompt-injection-v2.ipynb) | Text classification (SAFE/INJECTION) |
| mxbai-embed-large-v1 | [`notebooks/mxbai-embed-large-v1.ipynb`](notebooks/mxbai-embed-large-v1.ipynb) | Text embeddings (feature extraction) |
| all-MiniLM-L6-v2 | [`notebooks/all-minilm-l6-v2.ipynb`](notebooks/all-minilm-l6-v2.ipynb) | Text embeddings (sentence similarity) |
| multilingual-e5-base | [`notebooks/multilingual-e5-base.ipynb`](notebooks/multilingual-e5-base.ipynb) | Multilingual text embeddings |
| BGE Reranker Base | [`notebooks/bge-reranker-base.ipynb`](notebooks/bge-reranker-base.ipynb) | Cross-encoder reranking |
| BERT Base NER | [`notebooks/bert-base-ner.ipynb`](notebooks/bert-base-ner.ipynb) | Named entity recognition |
| BART Large MNLI | [`notebooks/bart-large-mnli.ipynb`](notebooks/bart-large-mnli.ipynb) | Zero-shot text classification |
| RoBERTa Base SQuAD2 | [`notebooks/roberta-base-squad2.ipynb`](notebooks/roberta-base-squad2.ipynb) | Extractive question answering |
| DistilBART CNN Summarization | [`notebooks/distilbart-cnn-summarization.ipynb`](notebooks/distilbart-cnn-summarization.ipynb) | Abstractive text summarization |

## Wave 2 — Enterprise RAG, Finance, Healthcare & Multilingual

| Product | Notebook | Task |
|---|---|---|
| MS-MARCO MiniLM-L6 Reranker | [`notebooks/ms-marco-minilm-l6-reranker.ipynb`](notebooks/ms-marco-minilm-l6-reranker.ipynb) | Cross-encoder reranking (fast) |
| MS-MARCO MiniLM-L12 Reranker | [`notebooks/ms-marco-minilm-l12-reranker.ipynb`](notebooks/ms-marco-minilm-l12-reranker.ipynb) | Cross-encoder reranking (precise) |
| GTE Multilingual Reranker Base | [`notebooks/gte-multilingual-reranker-base.ipynb`](notebooks/gte-multilingual-reranker-base.ipynb) | Multilingual cross-encoder reranking |
| all-mpnet-base-v2 | [`notebooks/all-mpnet-base-v2-embeddings.ipynb`](notebooks/all-mpnet-base-v2-embeddings.ipynb) | High-quality English sentence embeddings |
| BGE-M3 Multilingual Hybrid | [`notebooks/bge-m3-multilingual-hybrid.ipynb`](notebooks/bge-m3-multilingual-hybrid.ipynb) | Multilingual hybrid retrieval (dense+sparse+colbert) |
| Multilingual-E5-Small | [`notebooks/multilingual-e5-small.ipynb`](notebooks/multilingual-e5-small.ipynb) | Fast multilingual embeddings (100 languages) |
| Paraphrase Multilingual MPNet | [`notebooks/paraphrase-multilingual-mpnet.ipynb`](notebooks/paraphrase-multilingual-mpnet.ipynb) | Cross-lingual semantic similarity (50 languages) |
| Multilingual-E5-Large | [`notebooks/multilingual-e5-large.ipynb`](notebooks/multilingual-e5-large.ipynb) | High-accuracy multilingual embeddings (100 languages) |
| FinBERT Financial Sentiment | [`notebooks/finbert-financial-sentiment.ipynb`](notebooks/finbert-financial-sentiment.ipynb) | Financial news/filing sentiment analysis |
| Multilingual Sentiment (6 Languages) | [`notebooks/multilingual-sentiment-6lang.ipynb`](notebooks/multilingual-sentiment-6lang.ipynb) | 5-star review sentiment (EN/DE/FR/ES/IT/NL) |
| DistilBERT NER English | [`notebooks/distilbert-ner-english.ipynb`](notebooks/distilbert-ner-english.ipynb) | Fast English named entity recognition |
| Biomedical NER (107 Entities) | [`notebooks/biomedical-ner-all.ipynb`](notebooks/biomedical-ner-all.ipynb) | Clinical/pharma entity extraction |

## Prerequisites

- An AWS account subscribed to the product in AWS Marketplace
- An execution role with `AmazonSageMakerFullAccess`
- `pip install -U sagemaker boto3`

## Notes

- The model runs entirely inside your own AWS account. Text is not sent to any
  external service.
- Endpoints bill per hour for as long as they exist. Every notebook ends with a
  teardown cell — run it.
- Wave 2 models support both real-time inference (`deploy`) and batch transform
  for large-scale document processing.

## Support

support@waltsoft.net
