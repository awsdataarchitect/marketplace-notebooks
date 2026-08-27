# AWS Marketplace ML Model Notebooks

Sample notebooks for 34 SageMaker ML models available on [AWS Marketplace](https://aws.amazon.com/marketplace/search/results?CREATOR=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c&FULFILLMENT_OPTION_TYPE=SAGEMAKER_MODEL&filters=CREATOR%2CFULFILLMENT_OPTION_TYPE). All models run on `ml.m5.xlarge` (CPU, no GPU required).

## Models

| Notebook | Task | HuggingFace Model | Size | AWS Marketplace |
|---|---|---|---|---|
| [BGE Large EN v1.5](notebooks/bge-large-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-large-en-v1.5 | 796MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-ojxdraj4oledq) |
| [BGE Base EN v1.5](notebooks/bge-base-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-base-en-v1.5 | 238MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-itxv37aowdu6w) |
| [BGE Small EN v1.5](notebooks/bge-small-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-small-en-v1.5 | 73MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-ve2ckii4jsz3m) |
| [mxbai-embed-large-v1](notebooks/mxbai-embed-large-v1.ipynb) | Text Embeddings | mixedbread-ai/mxbai-embed-large-v1 | 590MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-63f6m2fcncrwg) |
| [all-MiniLM-L6-v2](notebooks/all-minilm-l6-v2.ipynb) | Text Embeddings | sentence-transformers/all-MiniLM-L6-v2 | 80MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-l7xvngtsasawi) |
| [all-mpnet-base-v2](notebooks/all-mpnet-base-v2-embeddings.ipynb) | Text Embeddings | sentence-transformers/all-mpnet-base-v2 | 438MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-kbnor7nv3st5u) |
| [multilingual-e5-base](notebooks/multilingual-e5-base.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-base | 622MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-4eb7o2f2yma7o) |
| [multilingual-e5-small](notebooks/multilingual-e5-small.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-small | 470MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-lhedmusf6hwk6) |
| [paraphrase-multilingual-mpnet](notebooks/paraphrase-multilingual-mpnet.ipynb) | Multilingual Embeddings | sentence-transformers/paraphrase-multilingual-mpnet-base-v2 | 1.1GB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-ng255yz3p3bha) |
| [BGE-M3 Multilingual Hybrid](notebooks/bge-m3-multilingual-hybrid.ipynb) | Hybrid Retrieval | BAAI/bge-m3 | 1.1GB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-y6u5flacvy5xk) |
| [BGE Reranker Base](notebooks/bge-reranker-base.ipynb) | Reranking | BAAI/bge-reranker-base | 943MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-kgk43qbgoytzi) |
| [MS-MARCO MiniLM-L6 Reranker](notebooks/ms-marco-minilm-l6-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-6-v2 | 90MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-ixdwjbmfr4tdm) |
| [MS-MARCO MiniLM-L12 Reranker](notebooks/ms-marco-minilm-l12-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-12-v2 | 134MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-la7ol5wbc4bsc) |
| [MS-MARCO MiniLM-L4 Reranker](notebooks/ms-marco-minilm-l4-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-4-v2 | 23MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-vuvoy2k6qfqeq) |
| [DeBERTa Prompt Injection v2](notebooks/deberta-v3-prompt-injection-v2.ipynb) | Security / LLM Guardrails | protectai/deberta-v3-base-prompt-injection-v2 | 628MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-dmh2wwx4moqzq) |
| [Toxic Content Detector](notebooks/toxic-content-detector.ipynb) | Content Moderation | unitary/toxic-bert | 110MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-zwigeadh4rrn4) |
| [BERT Base NER](notebooks/bert-base-ner.ipynb) | Named Entity Recognition | dslim/bert-base-NER | 384MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-kljm3cibleqsc) |
| [DistilBERT NER English](notebooks/distilbert-ner-english.ipynb) | Named Entity Recognition | elastic/distilbert-base-uncased-finetuned-conll03-english | 260MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-apxamlrsf277w) |
| [Biomedical NER](notebooks/biomedical-ner-all.ipynb) | Medical NER | d4data/biomedical-ner-all | 268MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-hqxancvrkug6w) |
| [XLM-RoBERTa Language Detector](notebooks/xlm-roberta-language-detect.ipynb) | Language Identification | papluca/xlm-roberta-base-language-detection | 278MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-ft4e3vtqxrnmu) |
| [Emotion Detection RoBERTa](notebooks/emotion-detection-roberta.ipynb) | Emotion Analysis | j-hartmann/emotion-english-distilroberta-base | 83MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-t5glaz4iilbaq) |
| [FinBERT Financial Sentiment](notebooks/finbert-financial-sentiment.ipynb) | Finance Sentiment | ProsusAI/finbert | 438MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-q7k732f7honkw) |
| [Multilingual Sentiment 6-Lang](notebooks/multilingual-sentiment-6lang.ipynb) | Multilingual Sentiment | nlptown/bert-base-multilingual-uncased-sentiment | 669MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-g7lzzchrbi4ge) |
| [TinyBERT Sentiment](notebooks/tinybert-fast-sentiment.ipynb) | Sentiment Analysis | philschmid/tiny-bert-sst2-distilled | 15MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-exwucatfeso5m) |
| [BART Large MNLI](notebooks/bart-large-mnli.ipynb) | Zero-Shot Classification | facebook/bart-large-mnli | 905MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-lztg56x3qti64) |
| [MiniLM NLI Zero-Shot](notebooks/minilm-nli-zero-shot.ipynb) | Zero-Shot Classification | cross-encoder/nli-MiniLM2-L6-H768 | 71MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-6jgrktr3235hq) |
| [RoBERTa Base SQuAD2](notebooks/roberta-base-squad2.ipynb) | Extractive QA | deepset/roberta-base-squad2 | 438MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-5r6ihji6kfznc) |
| [DistilBART CNN Summarization](notebooks/distilbart-cnn-summarization.ipynb) | Summarization | sshleifer/distilbart-cnn-12-6 | 819MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-a6s5pykebmtgm) |
| [Whisper Tiny](notebooks/whisper-tiny-multilingual.ipynb) | Speech Recognition | openai/whisper-tiny | 39MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-d4zu67ub74nvc) |
| [Whisper Base](notebooks/whisper-base-multilingual.ipynb) | Speech Recognition | openai/whisper-base | 74MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-uocqw2snlruxi) |
| [Whisper Small](notebooks/whisper-small-multilingual.ipynb) | Speech Recognition | openai/whisper-small | 244MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-hyiniwytzhcva) |
| [Wav2Vec2 English ASR](notebooks/wav2vec2-speech-recognition.ipynb) | Speech Recognition | facebook/wav2vec2-base-960h | 95MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-sjpv5cvsds53c) |
| [OPUS-MT EN-ES Translator](notebooks/opus-mt-en-es-translation.ipynb) | Machine Translation | Helsinki-NLP/opus-mt-en-es | 298MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-qwuebth2q6y5y) |
| [DistilGPT2 Text Generation](notebooks/distilgpt2-text-generation.ipynb) | Text Generation | distilbert/distilgpt2 | 82MB | [Subscribe](https://aws.amazon.com/marketplace/pp/prodview-qvnvapjxbsz5a) |

## Usage

1. Subscribe to the model on [AWS Marketplace](https://aws.amazon.com/marketplace/search/results?CREATOR=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c&FULFILLMENT_OPTION_TYPE=SAGEMAKER_MODEL&filters=CREATOR%2CFULFILLMENT_OPTION_TYPE)
2. Open the notebook in Amazon SageMaker Studio or a SageMaker Notebook Instance
3. Replace the placeholder ARN with your subscription ARN from the AWS Marketplace console
4. Run all cells

All models run on `ml.m5.xlarge` (CPU). No GPU required.

## License

Notebooks: MIT. Model licenses vary — see individual model cards on HuggingFace.
Apache-2.0 and MIT models only (no NC/SA/GPL licenses in this catalog).