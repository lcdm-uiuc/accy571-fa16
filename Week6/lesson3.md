# Week 6 Lesson 3 #
## Introduction to Supervised Learning ##

In this lesson, you will gain an introduction to Supervised Learning,
specifically via an introduction to several basic supervised learning algorithms: the Nearest neighbor algorithm, support vector machine, and Naive Bayes.  The nearest neighbor algorithm, more generally known as k-nearest neighbor is one of the simplest machine learning algorithms to learn, and often provides a quick and easy benchmark comparison for more
advanced techniques. Support Vector Machine, or SVM, has historically been a very popular machine learning algorithm since it is both fairly
intuitive and rather powerful. SVM can be applied to both classification
problems, where is may be called SVC, and to regression problems.  Naive Bayes uses the probability for each Attribute belonging to a particular class to make predictions. The naive descriptor relates to the underlying assumption that these probabilities are independent, which is generally not the case. However, this assumption can often be used to easily obtain good results.

###Objectives ###

By the end of this lesson, you will be able to:

- Understand the basic concepts behind the k-nearest neighbor algorithm
- Be able to apply k-nn by using the scikit learn library
- Understand the basic concepts behind the SVM algorithm
- Be able to apply SVM by using the scikit learn library
- Understand the basic concepts behind the Naive Bayes algorithm
- Be able to apply Naive Bayes by using the scikit learn library
- Understand the class of problems where these different algorithms are appropriate.

### Time Estimate ###

Approximately 3 hours.

### Readings ####

_Course Notebook_

- Explore the course [knn][l1nb]
IPython Notebook on the course JupyterHub server.

- Explore the course [SVM][l2nb]
IPython Notebook on the course JupyterHub server.

- Explore the course [Naive Bayes][l3nb]
IPython Notebook on the course JupyterHub server.

_Other Material_

- Dato Blog post on [classification metrics][bcm]
- Dato Blog post on [regression metrics][brm]
- Wikipedia Article on [classification metrics][wcm]
- A discussion of [using k-nn][yknn]
- An introduction to [k-nearest neighbors][knnb]

- An introductory discussion on [using SVM][isvm]
- A [simple introduction][sisvm] to svm
- [Understanding SVM][usvm] with code
- An overview of the [math behind SVM][msvm]

- An introduction to [Naive Bayes][inb]
- An blog introduction to [Naive Bayes][bnb]


## Optional Readings ##

- Scikit Learn [knn][sknn] documentation
- Discussion of [using knn in scikit learn][dknn]
- Kaggle video blog post on [Using k-NN][kknnb]

- Scikit Learn [svm][ssvm] documentation
- Tutorial on [SVM][tsvm]
- (Advanced) Blog post on [Using SVM][absvm]

- Scikit Learn [NB][snb] documentation
- Discussion on [improving Naive Bayes][dinb]
- Discussion of [using NV][unb] for text processing.

- Section 2.2 (KNN subsection) from [Introduction to Statistical Learning][isl]  by
Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani

- Section 13.3 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

- Chapter 9 from [Introduction to Statistical Learning][isl]  by
Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani

- Chapter 12 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

- Section 6.3.3 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

_Safari Online Books_

- **Chapter 12: k-Nearest Neighbors** from _Data Science from Scratch_, by Joel Grus.
- **Chapter 13: Naive Bayes** from _Data Science from Scratch_, by Joel Grus.

- First three sections in **Chapter 6. Similarity, Neighbors, and
Clusters** from _Data Science for Business_ by Foster Provost and Tom
Fawcett.


- **Section 9.3: Support Vector Machines** from _Data Mining: Concepts
and Techniques_, 3rd Edition by Jiawei Han, Micheline Kamber, and Jian
Pei.

- **Section 8.3 Bayes Classification Methods** from _Data Mining: Concepts
and Techniques_, 3rd Edition by Jiawei Han, Micheline Kamber, and Jian
Pei.

------

[l1nb]: notebooks/intro2knn.ipynb
[l2nb]: notebooks/intro2svm.ipynb
[l3nb]: notebooks/intro2nb.ipynb


[snb]: http://scikit-learn.org/stable/modules/naive_bayes.html
[unb]: http://blog.yhat.com/posts/naive-bayes-in-python.html
[bnb]: http://machinelearningmastery.com/naive-bayes-classifier-scratch-python/
[inb]: http://www.analyticsvidhya.com/blog/2015/09/naive-bayes-explained/
[dinb]: http://machinelearningmastery.com/better-naive-bayes/

[esl]: http://statweb.stanford.edu/~tibs/ElemStatLearn/

[isvm]: http://www.yaksis.com/posts/why-use-svm.html
[msvm]: http://www.svm-tutorial.com/2014/11/svm-understanding-math-part-1/
[ssvm]: http://scikit-learn.org/stable/modules/svm.html
[tsvm]: http://research.microsoft.com/en-us/um/people/cburges/papers/svmtutorial.pdf
[absvm]: https://www.quantstart.com/articles/Support-Vector-Machines-A-Guide-for-Beginners
[sisvm]: http://www.analyticsvidhya.com/blog/2014/10/support-vector-machine-simplified/
[usvm]: http://www.analyticsvidhya.com/blog/2015/10/understaing-support-vector-machine-example-code/


[isl]: http://www-bcf.usc.edu/~gareth/ISL/


[bcm]: http://blog.dato.com/how-to-evaluate-machine-learning-models-part-2a-classification-metrics
[brm]: http://blog.dato.com/how-to-evaluate-machine-learning-models-part-2b-ranking-and-regression-metrics
[wcm]: https://en.wikipedia.org/wiki/Precision_and_recall
[sknn]: http://scikit-learn.org/stable/modules/neighbors.html
[yknn]: http://blog.yhat.com/posts/classification-using-knn-and-python.html
[knnb]: http://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/
[kknnb]: http://blog.kaggle.com/2015/04/30/scikit-learn-video-4-model-training-and-prediction-with-k-nearest-neighbors/

[dknn]: http://bigdataexaminer.com/uncategorized/k-nearest-neighbors-and-curse-of-dimensionality-in-python-scikit-learn/
