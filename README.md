## 20newsgroup featurization

This project focuses more on featurization of a text corpus than the prediction. It explores vectorization via TF-IDF, both a custom and pretrained word2vec implementation, and from BERT.

### Environment

The notebook was created in AWS Sagemaker using the following:

* **Image**: `tensorflow-2.10-cpu-py39-ubuntu20.04-sagemaker-v1`
* **Instance**: `ml.t3.xlarge` (4vCPU + 16 GiB)

This setup will allow the notebook to run thoroughly, though the extra machinery is mostly to support the word2vec and BERT sections. The sklearn sections were initially built using the base Data Science image on an ml.t3.medium instance.

There are cells that will install the additional needed modules for the word2vec portion of the notebook. However, there is also a `requirements.txt` if needed.