# Contains Offensive Language

Built an ML model and SGD pipeline for finding and classifying hate speech

The X variable is the Tweet that has been cleaned of symbols and other bad information, such as 'RT' and 'HTML'

The y variable is the classfication, 0 for not hate speech and 1 for hate speech

Pipeline:

CountVectorizer - Turn text into matrix of token counts

TfidfTransformer - Turns CountVectorizer matrix into normalized TF representation

SGD Classfier - Implements linear models with stochastic gradient descent learning, as arrays of floating point values
