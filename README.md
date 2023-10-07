# NLP-Assignment 1

For installing the needed libraries, please run the below command :
pip install -r requirements.txt

**ngram.ipynb** - Main notebook containing all functions for prepreocessing, computing various counts, probablities and smoothing methods for ngram models (unigram and bigram) and their execution on given datasets.

Descriptions for the tokenization outputs and probabilities computes written to text files :

1. **Unsmoothed ngrams** - After pre-processing and tokenizing the training and validation dataset are written to *tokenized_train.txt* and *tokenized_val.txt*. The unsmoothed probabilities can be found in the files *unsmoothed_bigram_prob.txt* and *unsmoothed_unigram_prob.txt*.
2. **Unknown word handling** - Tokenized files for training and validation sets using "<UNK>" can be found in *tokenized_unk_train.txt* and *tokenized_unk_val.txt* The ngram probabilities after unknown word handling can be found in the files *unk_bigram_prob.txt* and *unk_unigram_prob.txt*.
3. **Add-1 laplace smoothing** - The ngram probabilities after using Laplace Smoothing technique can be found in the files *add1_unigram_prob.txt* and *add1_bigram_prob.txt*.
4. **Add-k smoothing** - The ngram probabilities after using Add-k Smoothing technique can be found in the files *addk_unigram_prob.txt* and *addk_bigram_prob.txt*.
5. **Linear interpolation** - The bigram probabilities after using Linear Interpolation Smoothing technique can be found in the file *interpolation_bigram_prob.txt*.


