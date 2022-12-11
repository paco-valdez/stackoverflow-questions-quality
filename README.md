# Classifying Question Quality of StackOverflow. 
### MIDS w266 Fall 2022

#### Francisco Valdez de la Fuente
#### paco.valdez@berkeley.edu


## Abstract
StackOverflow (SO) is a popular online platform for developers to ask and answer programming-related questions. This paper proposes a natural language processing (NLP) approach based on popular transformer NLP models to classify the quality of SO questions. We use a dataset of labeled questions based on score and popularity and apply different BERT-based models and a text-to-text transformer model for a multiclass classification task. Our experiments show that the best approach using T5, a text-to-text transformer, achieves a global accuracy of 39% and a maximum precision of 52% for one of the classes.

## [Full Report](https://github.com/pacofvf/stackoverflow-questions-quality/blob/main/Francisco%20Valdez%20-%20Classifying%20Question%20Quality%20of%20StackOverflow%20-%20MIDS%20W266%20FALL%202022.pdf)

## Links to datasets
- Full History 2008 to 2022 https://huggingface.co/datasets/pacovaldez/stackoverflow-questions
- 2016 Only https://huggingface.co/datasets/pacovaldez/stackoverflow-questions-2016
