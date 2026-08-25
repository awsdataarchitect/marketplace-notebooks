# AWS Marketplace ML Model Notebooks

Production-ready Jupyter notebooks for 34 AWS Marketplace SageMaker ML models across 4 waves.
All models run on `ml.m5.xlarge` (CPU, no GPU required).

## Wave 1-3: 22 Public Models

| Model | Task | Size |
|---|---|---|
| BGE Large EN v1.5 | Embeddings | 796MB |
| BGE Small EN v1.5 | Embeddings | 73MB |
| BGE Base EN v1.5 | Embeddings | 238MB |
| mxbai-embed-large-v1 | Embeddings | 590MB |
| all-MiniLM-L6-v2 | Embeddings | 80MB |
| all-mpnet-base-v2 | Embeddings | 2920MB |
| multilingual-e5-base | Multilingual Embeddings | 622MB |
| multilingual-e5-small | Multilingual Embeddings | 527MB |
| paraphrase-multilingual-mpnet | Paraphrase Embeddings | 1932MB |
| BGE-M3 Multilingual Hybrid | Hybrid Retrieval | 1259MB |
| BGE Reranker Base | Reranking | 943MB |
| MS-MARCO MiniLM-L6 Reranker | Reranking | 178MB |
| MS-MARCO MiniLM-L12 Reranker | Reranking | 262MB |
| DeBERTa Prompt Injection v2 | Security/Moderation | 628MB |
| BERT Base NER | Named Entity Recognition | 384MB |
| DistilBERT NER English | Named Entity Recognition | 234MB |
| Biomedical NER | Medical NER | 234MB |
| FinBERT Financial Sentiment | Finance Sentiment | 387MB |
| Multilingual Sentiment 6-Lang | Multilingual Sentiment | 1778MB |
| BART Large MNLI | Zero-Shot Classification | 905MB |
| RoBERTa Base SQuAD2 | Question Answering | 438MB |
| DistilBART CNN Summarization | Summarization | 819MB |

## Wave 4: 12 New Niches (Launching)

| Model | Task | HuggingFace Model | Size |
|---|---|---|---|
| whisper-tiny-multilingual | Speech Recognition (99 langs) | openai/whisper-tiny | 167MB |
| whisper-base-multilingual | Speech Recognition | openai/whisper-base | 318MB |
| whisper-small-multilingual | Speech Recognition (enterprise) | openai/whisper-small | 1073MB |
| wav2vec2-speech-recognition | English ASR (Facebook) | facebook/wav2vec2-base-960h | 421MB |
| ms-marco-minilm-l4-reranker | Fastest Reranker (23MB) | cross-encoder/ms-marco-MiniLM-L-4-v2 | 574MB |
| xlm-roberta-language-detect | Language Identification (20 langs) | papluca/xlm-roberta-base-language-detection | 1636MB |
| emotion-detection-roberta | 7-Class Emotion Detection | j-hartmann/emotion-english-distilroberta-base | ~83MB |
| toxic-content-detector | Content Moderation | unitary/toxic-bert | ~110MB |
| tinybert-fast-sentiment | Fastest Sentiment (15MB) | philschmid/tiny-bert-sst2-distilled | ~15MB |
| opus-mt-en-es-translation | English to Spanish MT | Helsinki-NLP/opus-mt-en-es | ~298MB |
| distilgpt2-text-generation | Lightweight Text Generation | distilbert/distilgpt2 | ~82MB |
| minilm-nli-zero-shot | Fast Zero-Shot Classification | cross-encoder/nli-MiniLM2-L6-H768 | ~71MB |

## Usage

1. Subscribe to the model on [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=seller-i2nvvwkbxbqqu)
2. Open the notebook in Amazon SageMaker Studio or a SageMaker Notebook Instance
3. Replace the placeholder ARN with your subscription ARN from the AWS Marketplace console
4. Run all cells

All models run on `ml.m5.xlarge` (CPU). No GPU required.

## License

Notebooks: MIT. Model licenses vary — see individual model cards on HuggingFace.
Apache-2.0 and MIT models only (no NC/SA/GPL licenses in this catalog).
