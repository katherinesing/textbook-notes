1. Problems described by a list of formal, mathematical rules are easy for computers, but hard for humans. 
2. Problems hard to describe but intuitive and automatic for humans, such as recognizing spoken words or faces in images, are hard for computers.
3. This book is about deep learning, the solution for computers to such intuitive problems.
4. Deep learning is how computers learn from experience and an heirachy of concepts, with each concept defined by its relation to simpler concepts.
5. Picture a graph with layers showing concepts related to each next concept. The graph is many layers deep, hence the term "deep learning".
6. Knowledge base approach to artiﬁcial intelligence - Several artiﬁcial intelligence projects, such as Cyc (Lenat andG uha, 1989) have attempted without major success to hard-code knowledge about the world so that a computer can reason using logical inference rules. 
7. Machine learning - From the difficulties of the knowledge base approach, it was concluded that AI systems should be able to acquire knowledge by extracting patterns from raw data, aka "machine learning".
8. Simple machine learning algorithm and example use cases: logistic regression, to recommend cesarean section delivery; naive Bayes, to identify spam from legitimate email.
9. Performance of simple ML algos depends heavily on the representation of the input data. If the data is structured and indexed intelligently. Designing the right set of features to extract, then providing the features to a simple ML algorithm.
10. How to get the right representation of data? ML can do that too. "Representation learning" discovers the data representation, and also maps the representation to the output. This enables AI systems to adapt to new tasks.
11. Example of represntation learning algorithm is an autoencoder, comprised of an encoder function then a decoder function. Preserve as much info as possible but also make the final representation have various nice properties.
12. "Factors of variation" refer to underlying, often hidden causes that explain different patterns or changes within data, like pose, lighting, or expression in images, or speaker's age or accent in a voice, which models aim to learn or become invariant to.
