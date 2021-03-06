# Multi-label classifier of social support

This is a classifier for social support (emotional vs. nonemotional) with word embeddings trained by Word2Vec. 

All posts are from Alzconnected.com.

This project will enable us to answer the question, whether dementia caregivers receive the support they need from social support forums by classifying the support needed and support provided. We can further help caregivers by understanding the social support dynamics.

### Social support

There are several different ways to categorize social support, and most of them fall in two broad categories, emotional and non-emotional.

Emotional support: expression of empathy, love, caring

Non-emotional support: information, comment, advice


### Pretrained word embeddings (Word2Vec)

Posts (N = 467,802) on Alzconnected.com, 2011 – 2020.03
Vocabulary: 243,607
Average word count: 143

### Multi-label classification with RNN

Activation function of sigmoid to ensure independent classification of multiple labels.

### Testing with N = 200

### Probing task

- Existing probing tasks of sentences (not significant)
- Probing with LIWC result (some linguistic features with high correlation)

### Double check with decision trees

- Higher accuracy

