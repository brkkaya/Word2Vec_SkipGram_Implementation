Word2Vec Skip-gram Implementation


Original Word2Vec word embeddings model (by Mikolov et al. in Efficient Estimation of Word Representations in Vector Space)

-In this project I focused on to re-implement this model to understand and visualize the how embeddings models work.

-Basically, this model takes an target word and trying to find to words on its left and right. 
Like a moving window on the corpus takes the word on the middle as center word the words on its right and left as context word.

-During the training each center word forward through to neural-net then we calculate the loss according to context word.

-The model:

<img src="https://paperswithcode.com/media/methods/Screen_Shot_2020-05-26_at_2.04.55_PM.png"  width=300 height=400>


