# Fine-tuned SciBERT for sentiment amalysis for biotech/pharma

SciBERT is a BERT model trained on scientific text. You can learn more about SciBERT here:https://github.com/allenai/scibert/blob/master/README.md

_SciBERT is trained on papers from the corpus of semanticscholar.org. Corpus size is 1.14M papers, 3.1B tokens. We use the full text of the papers in training, not just abstracts.
SciBERT has its own vocabulary (scivocab) that's built to best match the training corpus. We trained cased and uncased versions. We also include models trained on the original BERT vocabulary (basevocab) for comparison._

Quote: **It results in state-of-the-art performance on a wide range of scientific domain nlp tasks.**

You can upload the pre-trained weights directly into your **PyTorch model**; please refer to [this]([url](https://pytorch.org/tutorials/beginner/saving_loading_models.html)) and [this]([url](https://blog.allenai.org/tutorial-how-to-upload-transformer-weights-and-tokenizers-from-allennlp-to-huggingface-ecf6c0249bf)) guides if you require assistance.

Please reach out with any questions and suggestions.
