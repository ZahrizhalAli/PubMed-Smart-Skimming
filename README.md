# PubMed Abstract Classifier-Text Classification

Made by : Zahrizhal Ali
The PubMed Abstract Classifier is a machine learning project that aims to classify abstracts from medical research articles using natural 
language processing techniques. This comprehensive documentation provides an in-depth guide to the project, including its features, 
installation instructions, usage, and data sources.

Tech Used: 
## Features
* Utilizes PubMed abstract data for training and evaluation.
* Implements state-of-the-art machine learning algorithms for text classification.
* Provides evaluation metrics to assess the performance of the classifier.
* Includes data preprocessing and feature engineering techniques.
* Allows for customization and fine-tuning of the classifier.

## Data Sources
The PubMed Abstract Classifier project requires PubMed abstract data for training and evaluation. You can obtain such data from 
the PubMed database or other reliable sources that provide access to medical research articles. 
Ensure the data is in a suitable format, such as JSON or CSV, with the necessary information, including the abstract text and the corresponding labels or categories.

You can find more detail about the dataset link and paper [here](https://paperswithcode.com/dataset/pubmed-rct) and you can find the dataset [here](clone https://github.com/Franck-Dernoncourt/pubmed-rct.git).

## Experiments
| Experiment | Accuracy  | Precision    | Recall | F1-Score|
| :---:   | :---: | :---: |:---:|:---:|
|model_0_baseline	| 72.183238	| 0.783563 |	0.721832	| 0.744740 |
|model_1_custom_token_embedding	|81.345161|	0.820827|	0.813452	|0.816229|
|model_2_pretrained_token_embedding	|69.952337	|0.715874|	0.699523|	0.705446|
|model_3_custom_char_embedding	|34.085794	|0.932419|	0.340858	|0.480187|
|model_4_hybrid_char_token_embedding	|76.161790	|0.773674	|0.761618|	0.765332|
|model_5_positional_char_token_embedding_DAN|	84.334039|	0.843086|	0.843340|	0.840933|
|model_6_positional_char_token_embedding_transformer	|86.091619|	0.860752|	0.860916|	0.858282|

![image](https://github.com/ZahrizhalAli/PubMed-Smart-Skimming/assets/58893316/fddb84ea-ea95-42fd-95d2-6817e1445b28)

The PubMed Abstract Classifier project provides a powerful tool for automatically categorizing medical research abstracts. 
By utilizing deep learning and natural language processing techniques, it allows users to extract meaningful insights from a vast amount of scientific literature. 
Whether for research, information retrieval, or trend analysis, this project empowers users to efficiently analyze and classify PubMed abstracts.
