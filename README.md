# Question-Answer-and-Finetuning-a-BERT-model-with-SQUAD-dataset



https://colab.research.google.com/drive/1ubWPPPmFfWZ_faejaBsinYJrK4x5nJRA?usp=sharing 


# Objective:

The objective of this ICP is to Question-Answer and Finetuning a BERT model with SQUAD dataset.

# Approaches

At first, necessary libraries are imported. The dataset is loaded from Squad_v2 then tokenized and splitted. After tokenization necessary BERT class and methods 
are defined and Fine-tuned. BERT transformer performance is compared with different varient of BERT transformer.

# Datasets

For this ICP, dataset are used from Squad_V2 dataset. the dataset is extracted from Squad_v2 website in non relation format 
and sampled with BERT tokenizer and saved in google drive

# Results:

Results are generated with sklearn library with two BERT classifier variants. With "distilbert-base-uncased" BERT variant , F1 score is 69% 
and "distilbert-base-cased" BERT variant, F1 score is 61%.

                                        BERT Variant            F1
                               "distilbert-base-uncased"        69%
                               "distilbert-base-cased"          61%

# Challenges

For this icp, I tried to implement my data. but it is showing a lot of errors.

# Planned Work

At first, BERT library is installed and implemented and BERT tokenizer is implemented and dataset is classified. BERT performance is compared with various BERT transformer.
