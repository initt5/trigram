# trigram
This project is attempt of implementation character based language model used to generate new names. This project was deeply inspired by Andrej Karpathy's series, and especially by his implementation of the bigram model. I extended his idea of a trigram model and implemented the idea of a mixture model from [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf). This project is only intended for educational purposes.

In summary, models implemented are:
- Trigram, using 1x54 and 1x729 encoding
- MLP, using embeddings
- Mixture model, implemented from [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) with the help of [N-gram language models article](https://medium.com/mti-technology/n-gram-language-models-b125b9b62e58) to implement the EM algorithm.

The only requirament requirement is [Pytorch](https://pytorch.org/).
