1. In machine learning and data mining, a string kernel is a kernel function that operates on strings, i.e. finite sequences of symbols that need not be of the same length. String kernels can be intuitively understood as functions measuring the similarity of pairs of strings: the more similar two strings a and b are, the higher the value of a string kernel K(a, b) will be.  
《Text Classification Using String Kernels》


2、输入n-gram，可以计算每个n-gram在所有协议的语义空间中的向量表示(word2vec glove bert)，为了让词少一些，可以让块大致相同就算一样，以减少词典的量。  
每个packet的向量表示就是其内所有n-gram的平均，整个协议的向量表示也就是所有packet的平均
新来一个packet就用它看和哪个协议向量最接近  

或者用机器学习的方法来做，特征就是包向量


3、不用LDA，换一种方法做关键词提取
4、NLP的文档分类方法用上来
5、增量学习，强化学习，深度学习