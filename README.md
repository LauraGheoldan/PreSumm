# Improving Text Summarisation on WikiHow Data using Transfer Learning

**This notebook presents our implementation for the COMP0087 - Statistical Natural Language Processing project.**

We focus on showcasing the power of using transfer learning on the text summarisation task using the BERT-based models BertSum ([Text Summarization with Pretrained Encoders](https://arxiv.org/abs/1908.08345)) on the WikiHow dataset [WikiHow: A Large Scale Text Summarization Dataset](https://arxiv.org/abs/1810.09305).

Implementation includes code from [PreSumm GitHub](https://github.com/nlpyang/PreSumm), modified to suit our research purposes.

The complete version (complete.jpynb) goes through the WikiHow dataset pre-processing, models training and evaluation.

includes the pre-trained BertSumExt model obtained from [here](https://drive.google.com/file/d/1kKWoV0QCbeIuFt85beQgJ4v0lujaXobJ/view), the model we trained from scratch and our best performing model trained using transfer learning.

The demo version (demo.jpynb) compares the model trained from scratch and our best performing model using transfer learning on a small WikiHow test dataset.
