# CS4248 Project
This project was submitted as the final project for the National University of Singapore's module CS4248 Natural language Processing <br>
In this project, we aim to optimise DistilBERT's performance on Stanford Question Answering Dataset (SQuAD) with limited training time ($\leq$ 20 minutes on GPU T4(x2)) and limited dataset ($\leq$ 10,000 data points) while at the same time trying to reduce model size.<br>
The following 3 experiments are done:
* Response-based Knowledge Distillation with BERT-Large as teacher model
* Appending various Convolutional Neural Network (CNN) and Long Short-Term memory (LSTM) based models after DistilBERT's last hidden layer
* Magnitude-based weight pruning to reduce model size

# Getting Started
## Requirements
* Jupyter Notebook
* Python 3.7 or later
* Highly recommended to use a GPU

## Executing Program
Open `CS4248 Project.ipynb` and run all. Ensure that `trained_start_bert_uncased_presoftmax` and `trained_end_bert_uncased_presoftmax` are located at the same folder as the `.ipynb` file.