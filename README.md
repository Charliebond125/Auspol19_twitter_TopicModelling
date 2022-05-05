# Auspol19_twitter_TopicModelling
This repository contains the Auspol 2019 Twitter dataset as .CSV. Initally pulled from Kaggle as part of the Auspol sentiment analysis competition.

In this dataset I will be looking to clean, analyse, perform feature extraction and finally use Latent Derichlet Allocation as described by DM Blei, AY Ng, MI Jordan - Journal of machine Learning research, 2003 - jmlr.org.

The toolkits used will be Gensim/NLTK, as they are the easiest to use out of the box, but also provide very nice hyperparameter tuning capabilities.

A lot of the material had been taken from the docs regarding gensim/nltk, however some coding snippets were repurposed from blogs and other sites to facilitate my own learning. Please see below for the references used in the project.

https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/
https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/
https://www.machinelearningplus.com/nlp/topic-modeling-python-sklearn-examples/
https://www.machinelearningplus.com/nlp/gensim-tutorial/

User MrEliptik provided a very nice script to pre process the documentation which was a great aid. In the end it was not used, as I could not make it compatible between NLTK and Spacy tokenization as they work in different ways, nonetheless it was super helpful in my own project and development.

https://gist.github.com/MrEliptik/b3f16179aa2f530781ef8ca9a16499af
