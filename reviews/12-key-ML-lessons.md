[TOC]

# A few useful things to know about ML(oct,2012  citations:1900+)

- ML systems automatically learn programs from data/experience. They are widely used in various applications including web search, email spam classification and etc.

- However, by now(oct,2012), there still lacks in folk knowledge which are required for successful ML applications, thus avoiding producing more those ML less-than-ideal applications.

- 12 key lessons/tips/tricks

## LEARNING = REPRESENTATION + EVALUATION + OPTIMIZATION

- concepts; 1) representation: hyperthesis space of the learner such as, SVM which includes SVM w. all kinds of settings, if not in the sp., not be able to learn. 2)evaluation: the objetive/loss function, used to distinguish good classifier from bad ones, might differ from the one we 'd like to optimize . 3)optimization: needing a method to search among the classifiers in the language for
the highest-scoring one. **The choice of optimization technique is key to the efficiency of the
learner**.

- the table;
![](../images/three-components&#32;of&#32;learning&#32;algs.png)
>1)Not all combinations of one component from each
column of Table make equal sense. 2)Most textbooks are organized by representation,**the other components are equally important**.

## it's GENERALIZATION that COUNTS

- goal of generalization: generalize beyond the training set, e.g.: test set.

- data set split strategy: train-dev/val-test.

- cross validation;

## data alone is not enough

## overfitting has many faces

## intuition fails in high dims

## theoretical guarantees are not what they seem

## feature engineering is the key

## more data beats a clever alg

## learning many models not just one

## simplicity does not imply acc.

## representable does not imply learnable

## correlation does not imply casuality

