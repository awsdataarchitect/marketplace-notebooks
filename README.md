# AWS Marketplace ML Model Notebooks

Sample notebooks for 34 SageMaker ML models available on [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c). All models run on `ml.m5.xlarge` (CPU, no GPU required).

## Models

| Notebook | Task | HuggingFace Model | Size |
|---|---|---|---|
| [BGE Large EN v1.5](notebooks/bge-large-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-large-en-v1.5 | 796MB |
| [BGE Base EN v1.5](notebooks/bge-base-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-base-en-v1.5 | 238MB |
| [BGE Small EN v1.5](notebooks/bge-small-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-small-en-v1.5 | 73MB |
| [mxbai-embed-large-v1](notebooks/mxbai-embed-large-v1.ipynb) | Text Embeddings | mixedbread-ai/mxbai-embed-large-v1 | 590MB |
| [all-MiniLM-L6-v2](notebooks/all-minilm-l6-v2.ipynb) | Text Embeddings | sentence-transformers/all-MiniLM-L6-v2 | 80MB |
| [all-mpnet-base-v2](notebooks/all-mpnet-base-v2-embeddings.ipynb) | Text Embeddings | sentence-transformers/all-mpnet-base-v2 | 438MB |
| [multilingual-e5-base](notebooks/multilingual-e5-base.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-base | 622MB |
| [multilingual-e5-small](notebooks/multilingual-e5-small.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-small | 470MB |
| [paraphrase-multilingual-mpnet](notebooks/paraphrase-multilingual-mpnet.ipynb) | Multilingual Embeddings | sentence-transformers/paraphrase-multilingual-mpnet-base-v2 | 1.1GB |
| [BGE-M3 Multilingual Hybrid](notebooks/bge-m3-multilingual-hybrid.ipynb) | Hybrid Retrieval | BAAI/bge-m3 | 1.1GB |
| [BGE Reranker Base](notebooks/bge-reranker-base.ipynb) | Reranking | BAAI/bge-reranker-base | 943MB |
| [MS-MARCO MiniLM-L6 Reranker](notebooks/ms-marco-minilm-l6-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-6-v2 | 90MB |
| [MS-MARCO MiniLM-L12 Reranker](notebooks/ms-marco-minilm-l12-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-12-v2 | 134MB |
| [MS-MARCO MiniLM-L4 Reranker](notebooks/ms-marco-minilm-l4-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-4-v2 | 23MB |
| [DeBERTa Prompt Injection v2](notebooks/deberta-v3-prompt-injection-v2.ipynb) | Security / LLM Guardrails | protectai/deberta-v3-base-prompt-injection-v2 | 628MB |
| [Toxic Content Detector](notebooks/toxic-content-detector.ipynb) | Content Moderation | unitary/toxic-bert | 110MB |
| [BERT Base NER](notebooks/bert-base-ner.ipynb) | Named Entity Recognition | dslim/bert-base-NER | 384MB |
| [DistilBERT NER English](notebooks/distilbert-ner-english.ipynb) | Named Entity Recognition | elastic/distilbert-base-uncased-finetuned-conll03-english | 260MB |
| [Biomedical NER](notebooks/biomedical-ner-all.ipynb) | Medical NER | d4data/biomedical-ner-all | 268MB |
| [XLM-RoBERTa Language Detector](notebooks/xlm-roberta-language-detect.ipynb) | Language Identification | papluca/xlm-roberta-base-language-detection | 278MB |
| [Emotion Detection RoBERTa](notebooks/emotion-detection-roberta.ipynb) | Emotion Analysis | j-hartmann/emotion-english-distilroberta-base | 83MB |
| [FinBERT Financial Sentiment](notebooks/finbert-financial-sentiment.ipynb) | Finance Sentiment | ProsusAI/finbert | 438MB |
| [Multilingual Sentiment 6-Lang](notebooks/multilingual-sentiment-6lang.ipynb) | Multilingual Sentiment | nlptown/bert-base-multilingual-uncased-sentiment | 669MB |
| [TinyBERT Sentiment](notebooks/tinybert-fast-sentiment.ipynb) | Sentiment Analysis | philschmid/tiny-bert-sst2-distilled | 15MB |
| [BART Large MNLI](notebooks/bart-large-mnli.ipynb) | Zero-Shot Classification | facebook/bart-large-mnli | 905MB |
| [MiniLM NLI Zero-Shot](notebooks/minilm-nli-zero-shot.ipynb) | Zero-Shot Classification | cross-encoder/nli-MiniLM2-L6-H768 | 71MB |
| [RoBERTa Base SQuAD2](notebooks/roberta-base-squad2.ipynb) | Extractive QA | deepset/roberta-base-squad2 | 438MB |
| [DistilBART CNN Summarization](notebooks/distilbart-cnn-summarization.ipynb) | Summarization | sshleifer/distilbart-cnn-12-6 | 819MB |
| [Whisper Tiny](notebooks/whisper-tiny-multilingual.ipynb) | Speech Recognition | openai/whisper-tiny | 39MB |
| [Whisper Base](notebooks/whisper-base-multilingual.ipynb) | Speech Recognition | openai/whisper-base | 74MB |
| [Whisper Small](notebooks/whisper-small-multilingual.ipynb) | Speech Recognition | openai/whisper-small | 244MB |
| [Wav2Vec2 English ASR](notebooks/wav2vec2-speech-recognition.ipynb) | Speech Recognition | facebook/wav2vec2-base-960h | 95MB |
| [OPUS-MT EN-ES Translator](notebooks/opus-mt-en-es-translation.ipynb) | Machine Translation | Helsinki-NLP/opus-mt-en-es | 298MB |
| [DistilGPT2 Text Generation](notebooks/distilgpt2-text-generation.ipynb) | Text Generation | distilbert/distilgpt2 | 82MB |

## Usage

1. Subscribe to the model on [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c)
2. Open the notebook in Amazon SageMaker Studio or a SageMaker Notebook Instance
3. Replace the placeholder ARN with your subscription ARN from the AWS Marketplace console
4. Run all cells

All models run on `ml.m5.xlarge` (CPU). No GPU required.

## License

Notebooks: MIT. Model licenses vary — see individual model cards on HuggingFace.
Apache-2.0 and MIT models only (no NC/SA/GPL licenses in this catalog).