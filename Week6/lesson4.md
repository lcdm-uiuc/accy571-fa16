# Week 6 Lesson 1 #
## Decision Trees and Ensemble Learning ##

In this lesson, you will gain an introduction to decision trees and ensemble learning. The decision tree is a basic machine learning algorithm that is frequently used to visualize (and thus understand) how the machine is making a classification or regression decision. While this algorithm is important on its own, it is also important since it forms the basis for many ensemble learning techniques, such as the popular random forest algorithm. Next, you will learn about two ensemble learning techniques: bagging, or bootstrap bootstrap aggregation, and boosting. Ensemble learning leverages the power of the crowd to make a more robust prediction. In machine learning, we can combine the predictions from many weak learners to make a more powerful learning algorithm. The weak learners can be trained on only part of the data (e.g., only some features). These predictions can then be combined via bagging to generate an improved estimate with reduced variance. The most popular ensemble technique is the random forest (RF) algorithm, which is available in the scikit learn library. Boosting generally involves an iterative combination of new weak leaners, possibly with weighting, into a stronger learner. This iterative process can result in longer training times as optimizations in combining new weak learners can become computationally more intensive than some competing algorithms. However, the application of the algorithm to make predictions is more responsive since the model has already been constructed. Two of the most popular ensemble techniques that employs boosting are the adaptive boosting (or Adaboost) algorithm and the gradient boosted decision tree (GBT) algorithm, both of which are available in the scikit learn library. 


###Objectives ###

By the end of this lesson, you will be able to:

- Understand the basic concepts behind the decision tree algorithm
- Be able to create and use a decision tree by using the scikit learn library
- Understand how this algorithm can be successfully applied to specific problem categories.
- Understand the basic concepts behind ensemble techniques and, in particular, bagging
- Understand the basic concepts behind the random forest algorithm
- Be able to apply RF by using the scikit learn library
- Understand how to use RF effectively for different types of learning problems.
- Understand the basic concepts behind ensemble techniques and, in particular, boosting
- Understand the basic concepts behind the adaptive boosting and gradient boosted tree algorithms
- Be able to apply Adaboost and GBT by using the scikit learn library
- Understand how to use these algorithms effectively for different types of learning problems.

### Time Estimate ###

Approximately 3 hours.

### Readings ####

_Course Notebook_

- Explore the course [dt][l1nb]
IPython Notebook on the course JupyterHub server.
- Explore the course [Random Forest][l2nb]
IPython Notebook on the course JupyterHub server.
- Explore the course [Gradient Bosted Decision Tree][l2nb]
IPython Notebook on the course JupyterHub server.

_Other Material_

- A [visual introduction][vdt] to machine learning
- Wikipedia article on [decision trees][wdt]
- Scikit Learn [decision tree][sdt] documentation

- Wikpedia article on [Bagging][wb]

- A short introduction to [Random Forests][frf]
- A lengthy presentation on [Random Forests in Python][yrfp]

- An [introduction to random forests][arf1] Part I
- An [introduction to random forests][arf2] Part II

- Wikpedia article on [Boosting][wb]
- A comparison between [Bagging and Boosting][cbb]
- A blog detailing how to use [Gradient Boosted Trees][bgbt] with a corresponding [Notebook][ngbt]


## Optional Readings ##

- A Kaggle [discussion on random forests][krf]
- Scikit Learn [Ensemble Techniques: Bagging][seba] documentation
- An overview of [ensemble methods][ema].

- Original [Random Forest][orf] article.

- Scikit Learn [Adaboost][sada] documentation
- Scikit Learn [Gradient Tree Boosting][sgbt] documentation

- Complete tutorial on [Gradient Boosting][tgbt].


- Section 8.1 (Decision Tree subsection) from [Introduction to Statistical Learning][isl]  by
Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani
- Section 9.2 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

- Sections 8.2.1 and 8.2.2 from [Introduction to Statistical Learning][isl]  by
Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani
- Section 8.7 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

- Sections 8.2.3 from [Introduction to Statistical Learning][isl]  by
Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani
- Chapter 10 from [Elements of Statistical Learning][esl] by Trevor
Hastie, Robert Tibshirani, and Jerome Friedman. Note this text is rather
mathematical in nature.

_Safari Online Books_

- **Chapter 17: Decision Trees** from _Data Science from Scratch_, by Joel Grus.
- **Chapter 3. Introduction to Predictive Modeling** from _Data Science for Business_ by Foster Provost and Tom
Fawcett.

- The Random Forest section in **Chapter 17: Decision Trees** from _Data Science from Scratch_, by Joel Grus.

-----

[l1nb]: notebooks/intro2dt.ipynb

[l2nb]: notebooks/intro2rf.ipynb

[l2nb]: notebooks/intro2gbt.ipynb

[seba]: http://scikit-learn.org/stable/modules/ensemble.html#bagging

[frf]: http://fastml.com/intro-to-random-forests/
[yrfp]: http://blog.yhat.com/posts/random-forests-in-python.html
[arf1]: http://www.analyticsvidhya.com/blog/2014/06/introduction-random-forest-simplified/
[arf2]: http://www.analyticsvidhya.com/blog/2015/09/random-forest-algorithm-multiple-challenges/
[krf]: https://www.kaggle.com/c/titanic/details/getting-started-with-random-forests

[wb]: https://en.wikipedia.org/wiki/Bootstrap_aggregating

[orf]: http://www.stat.berkeley.edu/~breiman/randomforest2001.pdf
[ema]: http://www.cs.ucl.ac.uk/fileadmin/UCL-CS/research/Research_Notes/RN_11_02.pdf


[vdt]: http://www.r2d3.us/visual-intro-to-machine-learning-part-1/
[wdt]: https://en.wikipedia.org/wiki/Decision_tree
[sdt]: http://scikit-learn.org/stable/modules/tree.html#decision-trees

[sada]: http://scikit-learn.org/stable/modules/ensemble.html#adaboost
[sgbt]: http://scikit-learn.org/stable/modules/ensemble.html#gradient-tree-boosting

[wb]: https://en.wikipedia.org/wiki/Boosting_(machine_learning)

[bgbt]: http://www.datarobot.com/blog/gradient-boosted-regression-trees/
[ngbt]: http://nbviewer.jupyter.org/urls/s3.amazonaws.com/datarobotblog/notebooks/gbm-tutorial.ipynb

[cbb]: http://fastml.com/what-is-better-gradient-boosted-trees-or-random-forest/

[tgbt]: http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3885826/


[isl]: http://www-bcf.usc.edu/~gareth/ISL/
[esl]: http://statweb.stanford.edu/~tibs/ElemStatLearn/
