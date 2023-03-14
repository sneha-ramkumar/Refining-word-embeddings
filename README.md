# Refining-word-embeddings
Word embeddings that can capture semantic and syntactic information from
contexts have been extensively used for various natural language processing tasks.
However, existing methods of learning context-based word embeddings typically
fail to capture sufficient sentiment information. This may result in words with
similar vector representations having an opposite sentiment polarity (e.g. good and
bad), thus degrading sentiment analysis performance. To overcome this problem,
recent studies have suggested learning sentiment embeddings to incorporate the
sentiment polarity (positive and negative) information from labeled corpora. This
study adopts another strategy to learn sentiment embeddings. Instead of creating
a new word embedding from labeled corpora, we propose a word vector refinement
model. A word vector refinement model that can be applied to any pre-trained
word vectors (e.g. Word2Vec and GloVe). The refinement model is based on
adjusting the vector representations of words such that they can be closer to both
semantically and sentimentally similar words and further away from sentimentally
dissimilar words. The advantage of this proposed method is that it can be applied
to any pretrained word embeddings. In addition, the intensity scores can provide
more fine-grained (real-valued) sentiment information than binary polarity labels to
guide the refinement process. Experimental results show that the proposed
method can improve conventional word embeddings and outperform previously
proposed sentiment embeddings for both binary and fine-grained classification on
Stanford Sentiment Treebank (SST).
