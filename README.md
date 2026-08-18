# Waltsoft AWS Marketplace — SageMaker Sample Notebooks

Sample notebooks for deploying Waltsoft machine learning products from AWS
Marketplace as Amazon SageMaker endpoints.

Each notebook is self-contained: subscribe to the product in AWS Marketplace, paste
the model package ARN shown for your Region, then run the cells top to bottom.

| Product | Notebook | Task |
|---|---|---|
| BGE Large EN v1.5 | [`notebooks/bge-large-en-v1-5.ipynb`](notebooks/bge-large-en-v1-5.ipynb) | Text embeddings (feature extraction) |

## Prerequisites

- An AWS account subscribed to the product in AWS Marketplace
- An execution role with `AmazonSageMakerFullAccess`
- `pip install -U sagemaker boto3`

## Notes

- The model runs entirely inside your own AWS account. Text is not sent to any
  external service.
- Endpoints bill per hour for as long as they exist. Every notebook ends with a
  teardown cell — run it.

## Support

support@waltsoft.net
