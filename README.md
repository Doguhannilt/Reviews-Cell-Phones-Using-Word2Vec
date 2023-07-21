<h1>Word2Vec</h1>

<lu>
	<li>Word2Vec is a popular natural language processing technique used to generate word embeddings, which are dense vector representations of words in a continuous vector space. It leverages the context of words in a large corpus to learn meaningful word embeddings, allowing similar words to have similar vector representations.</li>
</lu>

<h1>Word Embedding</h1>

<lu>
	<li>Word embedding is a numerical representation of words in a continuous vector space, where each word is mapped to a dense vector. These embeddings capture semantic relationships between words and are useful in various NLP tasks such as machine translation, sentiment analysis, and named entity recognition.</li>
</lu>

<h1>Parameters of Word2Vec</h1>

<lu>
	<li>Window: Sets the context window size for training, determining the number of words considered as context for each target word.</li>
	<li>Min_count: Specifies the minimum frequency of a word in the corpus to be considered during training.</li>
	<li>Workers: Controls the number of CPU cores used for parallelization during training.</li>
	<li>Size: Determines the dimensionality of the word embeddings.</li>
	<li>Sg (skip-gram): A boolean parameter specifying the training algorithm (skip-gram if True, CBOW if False).</li>
	<li>Hs (hierarchical softmax): A boolean parameter determining the training strategy (hierarchical softmax if True, negative sampling if False).</li>
	<li>Negative: The number of negative samples used during negative sampling.</li>
	<li>Iter: The number of training iterations (epochs) over the corpus and others such as cbow_mean, hashfxn, compute_loss, and callbacks.</li>
</lu>

<h1>Gensim</h1>

<lu>
	<li>Gensim is an open-source Python library for natural language processing that provides efficient tools for topic modeling, document similarity analysis, and word embedding training. It is widely used for Word2Vec training and offers easy-to-use interfaces for working with large text corpora and generating word embeddings.</li>
</lu>

<h1>Gensim VS Bert </h1>

<lu>
	<li>Word2Vec: Word2Vec is an unsupervised algorithm that generates word embeddings from large text corpora. It represents each word as a fixed-size vector based on its local context in a sentence, making it useful for tasks like word similarity and analogies. However, it lacks bidirectional understanding and doesn't capture broader context beyond individual words.</li>
	<li>BERT (Bidirectional Encoder Representations from Transformers): BERT is a pre-trained language model that uses transformer-based architecture. It captures bidirectional relationships between words and considers the entire context of a sentence. It provides contextualized word embeddings, enabling better understanding of word meaning within various contexts. BERT's versatility allows it to excel in numerous NLP tasks, including text classification, named entity recognition, and question answering.</li>
</lu>

<h1>Bidirectional Relationships</h1>
<lu>
	<li>Bidirectional relationships mean considering both the words before and after a target word to understand its meaning within a sentence. It helps capture the complete context and dependencies, leading to better comprehension of language nuances and sentence structures.</li>
</lu>
