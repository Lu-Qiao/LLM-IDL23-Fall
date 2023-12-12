# Nano-GPT - Building LLM from scratch
Carnegie Mellon University

Introduction to Deep Learning 2023 Fall

Lu Qiao, Ishu Wang

This project presents the development of a Large Language Model (LLM), aimed at improving text summarization and question-answering (QA) tasks. The presented model is pre-trained on a diverse textual corpus from the OpenWebText dataset and fine-tuned using the CNN/Daily Mail dataset for summarization and the Stanford Question Answering Dataset (SQuAD) for QA. The focus of this project is to enhance the model's ability to extract important details from long text and perform specific tasks by providing contextually accurate outputs. This approach not only demonstrates the model's practical application in natural language processing but also highlights the significance of attention mechanisms in augmenting LLMs' language comprehension and generation capabilities. 

# Organization of the repository
1. Tokenizer Vocabulary: 40000, 60000
2. Preprocessing dataset: OpenWebText, CNN//Daily Mail + SQuAD
3. Training Baseline Models:
4. Finetuning Baseline Model for Summary and QA task, Evalution:

# How to run the model

# Candidate Architectures for Baseline Model
## Figure 1. Candidate I
![LSTM drawio](https://github.com/Lu-Qiao/LLM-IDL23-Fall/assets/112424096/03fcb79d-9a05-4ea8-ba35-06f232faae8a)


## Figure 2. Candidate II
![encoder-decoder](https://github.com/Lu-Qiao/LLM-IDL23-Fall/assets/112424096/7fc257b3-f1b5-4b45-9add-8a4afafae12e)


## Figure 3. Candidate III, selected for Finetuning
![decoder-only drawio](https://github.com/Lu-Qiao/LLM-IDL23-Fall/assets/112424096/14b0b4a2-3fd7-42ed-9417-358c6e21554f)

