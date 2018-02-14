# Compared to human level performance
## Why to compare?
Bayes optimal error: top line never be surpassed
Accuracy grows until reaching human level, and then slow down

## Avoidable bias
Compare human level error(appro.  Bayes error) to training set error: reduce bias
Compare training set error to dev set error: reduce variance in learning algorithm (regularization, more training data)
Small percentage of diffrence in error is ok.

## Understanding human level performance
Human level error: proxy for Baye's error
Define human level error: the most experienced one in file; for deloyment or research, maybe a typical one is good to go
Normally, choose between avoiding bias / reducing variance: see which error difference is bigger? However, if they are similar, you may choose a more accurate human level error
Having an estimation of human level performance (no need to be 0% error) helps to make a decision: avoiding bias or reducing variance; until it surpasses human level performance

## Surpass human level performance
When surpassing, harder to make progress, but still able to
There are many problems where machine learning significantly surpasses human-level performance: online advertising, product recommendations, transit time estimation, loan approval
Why surpass? 
    - structured data (database)
    - not natural perception task
    - a lot of data
Surpassing human-level performance is often not easy, but given enough data there've been lots of deep learning systems have surpassed human-level performance on a single supervisory problem.


## Improve your model performance
Avoid bias:
  - train bigger model
  - train longer/better optimization algorithms (momentum, RMSPOP, Adom)
  - new nether architecture or better said, hyperparameters and this could include everything from changing the activation functions or changing the number of layers or hidden do this
Reduce variance:
  - more data
  - regularization (l2, dropout, data augmentation)

