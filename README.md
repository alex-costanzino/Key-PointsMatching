# Key-Points Matching in NLP

Argument mining is a recent and developing field of research in natural language processing. Essentially, argument mining involves automatically identifying argument structures in free text, such as the argument’s conclusion, premises, and reasoning scheme, as well as their interrelationships and counter-considerations.

One of the task that composes argument mining’s pipeline is key-point matching: given a sentence (typically an argument) and a key-point, determine whether the latter matches the proposed sentence.

The classification task can be also enriched with other features that may help to tell apart matching and non-matching pairs. In particular, in our scenario, also the topic and the stance of the argument have been integrated to provide context to the models.

Both unsupervised and supervised methods are experimented. In particular, clustering with GloVe embeddings, BERT vector representations and tf-idf have been endeavoured, as unsupervised method, in order to provide a baseline for more advanced methods. Subsequently, also two neural architectures have been assessed in order to exploit the training data available.

At the end, a comparison with a particular focus on the type of error made by each model has been performed.
