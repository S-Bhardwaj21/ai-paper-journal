# What problem is the paper trying to solve?
They tried to implement different methods to improve both the quality of the vectors and the training speed.They showed what the skip-gram model does using hierarchical softmax, and tried to improve the results using methods such as negative sampling,subsampling and Noise Contrastive Estimation. They proposed that word vectors should be replaced by phrase vectors to make the model learning better on semantic and linguistic relationships. Then, they applied subsampling methods on frequent and rare words in attempt to increase the accuracy of the learned vectors of the rare words.Results have shown negative sampling to better than both hierarchical softmax and even performing better than NCE. With subsampling, they improved the training speed several times and made the word representations significantly more accurate and most importantly, on a much larger dataset than taken by earlier attempts to do so.
# Why is this problem important?
- It was important to demonstrate that the words and phrases relationships show linear relationships
- Subsampling of the frequent words results in both faster training and significantly better representations of common words.
- Word vectors can be meaningfully combined using simple vector addition!!
- The Skip-gram model with their extensions outperforms all the other models in the quality of the learned representations.
# What approaches does the paper introduces?
- Noise Contractive Estimation
- Negative Sampling
- Subsampling
- Hierarchical softmax
# Key takeaways from this paper
The most crucial decisions that affects the performance are the choice of the model architecture, the size of the vectors, the subsampling rate, and the size of the training window.
# What I found interesting?
Word vectors can be combined using simple vector addition!
# What I still don't understand?
The approaches used,none of them.
