# Deep-Learning-Project

**Project for the Deep Learning course** - University of Bologna, Cesena Campus

**Authors**:
* Veronika Folin
* Anna Vitali
* Elena Yan

## Description of the project

-----------------------------------------------

### Objective

The aim of this project is to evaluate the performance of several deep learning models on the ***Grammatical Error Correction*** (*GEC*) task, which consists to transform a potentially wrong input sentence to a corrected version.

There are different types of errors within the input text, such as spelling, punctuation, grammatical, or words.

### Dataset

The dataset used for experiments is [C4 200M Synthetic Dataset](https://huggingface.co/datasets/liweili/c4_200m), a collection of 185M sentence pairs with grammatical errors generated from [C4 (Colossal Clean Crawled Corpus)](https://www.tensorflow.org/datasets/catalog/c4?hl=it).

### Models

We tested the following types of model:
- **Encoder-Decoder** with **Recurrent Neural Networks**
- **Transformer**

### Optimizer

- **Adam**
- **RMSprop**

### Loss Functions

- **categorical_crossentropy**
- **sparse_categorical_crossentropy**

### Evaluation Metrics

We used the following evaluation metrics to assess model performance:

- [**Bleu**](https://huggingface.co/spaces/evaluate-metric/bleu)
- [**Gleu**](https://huggingface.co/spaces/evaluate-metric/google_bleu)
- **Masked Accuracy**

## Implementation and results

-----------------------------------------------

You can find the work done in the final notebook, which is the `notebook.ipynb` file.

A summary of experiments' configuration and results are in the `experiment_results.xlsx` file.

