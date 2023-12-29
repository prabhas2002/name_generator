# Name Generator Neural Network Using Pytorch

This repository contains a neural network-based models for generating unique names. The model is trained on a dataset of names provided in the `names.txt` file.
The complete implementation dont use any inbuilt libraries or methods ,but only basic modules like numpy,Pytorch,matplotlib.

## Project Structure

- **`names.txt`**: Corpus of names used for training the models.

- **`1_Bigram_Model.ipynb`**: Notebook implementing a bigram model. It counts frequencies of character pairs and generates names based on probabilities.

- **`2_Bigram_Neural_Net.ipynb`**: Notebook implementing a bigram neural network. It uses the previous character to generate the next character in a name.

- **`3_Ngram_Neural_Net.ipynb`**: Notebook implementing an N-gram neural network. It uses the previous N characters to generate the next character in a name.

## Usage

1. **Dataset**: Ensure that the `names.txt` file contains the corpus of names you want to train on.

2. **Bigram Model**: Open and run the `1_Bigram_Model.ipynb` notebook to see the implementation of the bigram model.

3. **Bigram Neural Net**: Open and run the `2_Bigram_Neural_Net.ipynb` notebook to see the implementation of the bigram neural network.

4. **N-gram Neural Net**: Open and run the `3_Ngram_Neural_Net.ipynb` notebook to see the implementation of the N-gram neural network.

