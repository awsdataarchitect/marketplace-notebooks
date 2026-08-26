# AWS Marketplace ML Model Notebooks

Sample notebooks for 34 SageMaker ML models available on [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=seller-i2nvvwkbxbqqu). All models run on `ml.m5.xlarge` (CPU, no GPU required).

## Models

| Notebook | Task |
|---|---|
| [BGE Large EN v1.5](notebooks/bge-large-en-v1-5.ipynb) | Text Embeddings |
| [BGE Base EN v1.5](notebooks/bge-base-en-v1-5.ipynb) | Text Embeddings |
| [BGE Small EN v1.5](notebooks/bge-small-en-v1-5.ipynb) | Text Embeddings |
| [mxbai-embed-large-v1](notebooks/mxbai-embed-large-v1.ipynb) | Text Embeddings |
| [all-MiniLM-L6-v2](notebooks/all-minilm-l6-v2.ipynb) | Text Embeddings |
| [all-mpnet-base-v2](notebooks/all-mpnet-base-v2-embeddings.ipynb) | Text Embeddings |
| [multilingual-e5-base](notebooks/multilingual-e5-base.ipynb) | Multilingual Embeddings |
| [multilingual-e5-small](notebooks/multilingual-e5-small.ipynb) | Multilingual Embeddings |
| [paraphrase-multilingual-mpnet](notebooks/paraphrase-multilingual-mpnet.ipynb) | Multilingual Embeddings |
| [BGE-M3 Multilingual Hybrid](notebooks/bge-m3-multilingual-hybrid.ipynb) | Hybrid Retrieval |
| [BGE Reranker Base](notebooks/bge-reranker-base.ipynb) | Reranking |
| [MS-MARCO MiniLM-L6 Reranker](notebooks/ms-marco-minilm-l6-reranker.ipynb) | Reranking |
| [MS-MARCO MiniLM-L12 Reranker](notebooks/ms-marco-minilm-l12-reranker.ipynb) | Reranking |
| [MS-MARCO MiniLM-L4 Reranker](notebooks/ms-marco-minilm-l4-reranker.ipynb) | Reranking |
| [DeBERTa Prompt Injection v2](notebooks/deberta-v3-prompt-injection-v2.ipynb) | Security / LLM Guardrails |
| [Toxic Content Detector](notebooks/toxic-content-detector.ipynb) | Content Moderation |
| [BERT Base NER](notebooks/bert-base-ner.ipynb) | Named Entity Recognition |
| [DistilBERT NER English](notebooks/distilbert-ner-english.ipynb) | Named Entity Recognition |
| [Biomedical NER](notebooks/biomedical-ner-all.ipynb) | Medical NER |
| [XLM-RoBERTa Language Detector](notebooks/xlm-roberta-language-detect.ipynb) | Language Identification |
| [Emotion Detection RoBERTa](notebooks/emotion-detection-roberta.ipynb) | Emotion Analysis |
| [FinBERT Financial Sentiment](notebooks/finbert-financial-sentiment.ipynb) | Finance Sentiment |
| [Multilingual Sentiment 6-Lang](notebooks/multilingual-sentiment-6lang.ipynb) | Multilingual Sentiment |
| [TinyBERT Sentiment](notebooks/tinybert-fast-sentiment.ipynb) | Sentiment Analysis |
| [BART Large MNLI](notebooks/bart-large-mnli.ipynb) | Zero-Shot Classification |
| [MiniLM NLI Zero-Shot](notebooks/minilm-nli-zero-shot.ipynb) | Zero-Shot Classification |
| [RoBERTa Base SQuAD2](notebooks/roberta-base-squad2.ipynb) | Extractive QA |
| [DistilBART CNN Summarization](notebooks/distilbart-cnn-summarization.ipynb) | Summarization |
| [Whisper Tiny](notebooks/whisper-tiny-multilingual.ipynb) | Speech Recognition |
| [Whisper Base](notebooks/whisper-base-multilingual.ipynb) | Speech Recognition |
| [Whisper Small](notebooks/whisper-small-multilingual.ipynb) | Speech Recognition |
| [Wav2Vec2 English ASR](notebooks/wav2vec2-speech-recognition.ipynb) | Speech Recognition |
| [OPUS-MT EN-ES Translator](notebooks/opus-mt-en-es-translation.ipynb) | Machine Translation |
| [DistilGPT2 Text Generation](notebooks/distilgpt2-text-generation.ipynb) | Text Generation |

## Usage

1. Subscribe to the model on [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=seller-i2nvvwkbxbqqu)
2. Open the notebook in Amazon SageMaker Studio or a SageMaker Notebook Instance
3. Replace the placeholder ARN with your subscription ARN from the AWS Marketplace console
4. Run all cells

All models run on `ml.m5.xlarge` (CPU). No GPU required.

## License

Notebooks: MIT. Model licenses vary — see individual model cards on HuggingFace.
Apache-2.0 and MIT models only (no NC/SA/GPL licenses in this catalog).

