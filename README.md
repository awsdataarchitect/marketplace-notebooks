# AWS Marketplace ML Model Notebooks

Sample notebooks for 34 SageMaker ML models available on [AWS Marketplace](https://aws.amazon.com/marketplace/search/results?CREATOR=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c&FULFILLMENT_OPTION_TYPE=SAGEMAKER_MODEL&filters=CREATOR%2CFULFILLMENT_OPTION_TYPE). All models run on `ml.m5.xlarge` (CPU, no GPU required).

## Models

| Notebook | Task | HuggingFace Model | Size | AWS Marketplace |
|---|---|---|---|---|
| [BGE Large EN v1.5](notebooks/bge-large-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-large-en-v1.5 | 796MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ojxdraj4oledq) |
| [BGE Base EN v1.5](notebooks/bge-base-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-base-en-v1.5 | 238MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-itxv37aowdu6w) |
| [BGE Small EN v1.5](notebooks/bge-small-en-v1-5.ipynb) | Text Embeddings | BAAI/bge-small-en-v1.5 | 73MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ve2ckii4jsz3m) |
| [mxbai-embed-large-v1](notebooks/mxbai-embed-large-v1.ipynb) | Text Embeddings | mixedbread-ai/mxbai-embed-large-v1 | 590MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-63f6m2fcncrwg) |
| [all-MiniLM-L6-v2](notebooks/all-minilm-l6-v2.ipynb) | Text Embeddings | sentence-transformers/all-MiniLM-L6-v2 | 80MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-l7xvngtsasawi) |
| [all-mpnet-base-v2](notebooks/all-mpnet-base-v2-embeddings.ipynb) | Text Embeddings | sentence-transformers/all-mpnet-base-v2 | 438MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-kbnor7nv3st5u) |
| [multilingual-e5-base](notebooks/multilingual-e5-base.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-base | 622MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-4eb7o2f2yma7o) |
| [multilingual-e5-small](notebooks/multilingual-e5-small.ipynb) | Multilingual Embeddings | intfloat/multilingual-e5-small | 470MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-lhedmusf6hwk6) |
| [paraphrase-multilingual-mpnet](notebooks/paraphrase-multilingual-mpnet.ipynb) | Multilingual Embeddings | sentence-transformers/paraphrase-multilingual-mpnet-base-v2 | 1.1GB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ng255yz3p3bha) |
| [BGE-M3 Multilingual Hybrid](notebooks/bge-m3-multilingual-hybrid.ipynb) | Hybrid Retrieval | BAAI/bge-m3 | 1.1GB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-y6u5flacvy5xk) |
| [BGE Reranker Base](notebooks/bge-reranker-base.ipynb) | Reranking | BAAI/bge-reranker-base | 943MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-kgk43qbgoytzi) |
| [MS-MARCO MiniLM-L6 Reranker](notebooks/ms-marco-minilm-l6-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-6-v2 | 90MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ixdwjbmfr4tdm) |
| [MS-MARCO MiniLM-L12 Reranker](notebooks/ms-marco-minilm-l12-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-12-v2 | 134MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-la7ol5wbc4bsc) |
| [MS-MARCO MiniLM-L4 Reranker](notebooks/ms-marco-minilm-l4-reranker.ipynb) | Reranking | cross-encoder/ms-marco-MiniLM-L-4-v2 | 23MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-vuvoy2k6qfqeq) |
| [DeBERTa Prompt Injection v2](notebooks/deberta-v3-prompt-injection-v2.ipynb) | Security / LLM Guardrails | protectai/deberta-v3-base-prompt-injection-v2 | 628MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-dmh2wwx4moqzq) |
| [Toxic Content Detector](notebooks/toxic-content-detector.ipynb) | Content Moderation | unitary/toxic-bert | 110MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-zwigeadh4rrn4) |
| [BERT Base NER](notebooks/bert-base-ner.ipynb) | Named Entity Recognition | dslim/bert-base-NER | 384MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-kljm3cibleqsc) |
| [DistilBERT NER English](notebooks/distilbert-ner-english.ipynb) | Named Entity Recognition | elastic/distilbert-base-uncased-finetuned-conll03-english | 260MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-apxamlrsf277w) |
| [Biomedical NER](notebooks/biomedical-ner-all.ipynb) | Medical NER | d4data/biomedical-ner-all | 268MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-hqxancvrkug6w) |
| [XLM-RoBERTa Language Detector](notebooks/xlm-roberta-language-detect.ipynb) | Language Identification | papluca/xlm-roberta-base-language-detection | 278MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ft4e3vtqxrnmu) |
| [Emotion Detection RoBERTa](notebooks/emotion-detection-roberta.ipynb) | Emotion Analysis | j-hartmann/emotion-english-distilroberta-base | 83MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-t5glaz4iilbaq) |
| [FinBERT Financial Sentiment](notebooks/finbert-financial-sentiment.ipynb) | Finance Sentiment | ProsusAI/finbert | 438MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-q7k732f7honkw) |
| [Multilingual Sentiment 6-Lang](notebooks/multilingual-sentiment-6lang.ipynb) | Multilingual Sentiment | nlptown/bert-base-multilingual-uncased-sentiment | 669MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-g7lzzchrbi4ge) |
| [TinyBERT Sentiment](notebooks/tinybert-fast-sentiment.ipynb) | Sentiment Analysis | philschmid/tiny-bert-sst2-distilled | 15MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-exwucatfeso5m) |
| [BART Large MNLI](notebooks/bart-large-mnli.ipynb) | Zero-Shot Classification | facebook/bart-large-mnli | 905MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-lztg56x3qti64) |
| [MiniLM NLI Zero-Shot](notebooks/minilm-nli-zero-shot.ipynb) | Zero-Shot Classification | cross-encoder/nli-MiniLM2-L6-H768 | 71MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-6jgrktr3235hq) |
| [RoBERTa Base SQuAD2](notebooks/roberta-base-squad2.ipynb) | Extractive QA | deepset/roberta-base-squad2 | 438MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-5r6ihji6kfznc) |
| [DistilBART CNN Summarization](notebooks/distilbart-cnn-summarization.ipynb) | Summarization | sshleifer/distilbart-cnn-12-6 | 819MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-a6s5pykebmtgm) |
| [Whisper Tiny](notebooks/whisper-tiny-multilingual.ipynb) | Speech Recognition | openai/whisper-tiny | 39MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-d4zu67ub74nvc) |
| [Whisper Base](notebooks/whisper-base-multilingual.ipynb) | Speech Recognition | openai/whisper-base | 74MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-uocqw2snlruxi) |
| [Whisper Small](notebooks/whisper-small-multilingual.ipynb) | Speech Recognition | openai/whisper-small | 244MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-hyiniwytzhcva) |
| [Wav2Vec2 English ASR](notebooks/wav2vec2-speech-recognition.ipynb) | Speech Recognition | facebook/wav2vec2-base-960h | 95MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-sjpv5cvsds53c) |
| [OPUS-MT EN-ES Translator](notebooks/opus-mt-en-es-translation.ipynb) | Machine Translation | Helsinki-NLP/opus-mt-en-es | 298MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-qwuebth2q6y5y) |
| [DistilGPT2 Text Generation](notebooks/distilgpt2-text-generation.ipynb) | Text Generation | distilbert/distilgpt2 | 82MB | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-qvnvapjxbsz5a) |

## Small models

Compact models that run on small, low-cost instances (`ml.t2.medium` real-time, `ml.m5.large` batch). Each has a notebook below, and its listing carries the request/response example, deploy steps and measured results.

| Notebook | Task | HuggingFace Model | Size | Instances | AWS Marketplace |
|---|---|---|---|---|---|
| [TinyBERT-L2 Reranker](notebooks/tinybert-l2-reranker.ipynb) | Reranking | cross-encoder/ms-marco-TinyBERT-L2-v2 | 17.6MB | `ml.t2.medium` (real-time), `ml.m5.large` (batch) | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-aqkv2iue6pe2o) |
| [Email Spam Classifier](notebooks/bert-tiny-enron-spam-detection.ipynb) | Text Classification | mrm8488/bert-tiny-finetuned-enron-spam-detection | 17.6MB | `ml.t2.medium` (real-time), `ml.m5.large` (batch) | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-znxxqxm7joano) |
| [ALBERT Paraphrase Embeddings](notebooks/paraphrase-albert-small-embeddings.ipynb) | Text Embeddings | sentence-transformers/paraphrase-albert-small-v2 | 46.7MB | `ml.t2.medium` (real-time), `ml.m5.large` (batch) | [View in AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-5mcefklex2ils) |
| [MiniLM-L3 Paraphrase Embeddings](notebooks/paraphrase-minilm-l3-embeddings.ipynb) | Text Embeddings | sentence-transformers/paraphrase-MiniLM-L3-v2 | 69.6MB | `ml.t2.medium` (real-time), `ml.m5.large` (batch) | Public once its pipeline run finishes; link added after AWS indexes it |

## Usage

1. Open the model's AWS Marketplace listing from the table above, or browse all models in [AWS Marketplace](https://aws.amazon.com/marketplace/search/results?CREATOR=4bf1a800-d6fc-4c1f-8e88-76ef2dbfb77c&FULFILLMENT_OPTION_TYPE=SAGEMAKER_MODEL&filters=CREATOR%2CFULFILLMENT_OPTION_TYPE)
2. Open the notebook in Amazon SageMaker Studio or a SageMaker Notebook Instance
3. Replace the placeholder with the model package ARN shown on the product's launch page for your Region
4. Run all cells

The models in the first table run on `ml.m5.xlarge` (CPU); the small models list their own instance types above. No GPU required.

## License

Notebooks: MIT. Model licenses vary — see individual model cards on HuggingFace.
Apache-2.0 and MIT models only (no NC/SA/GPL licenses in this catalog).