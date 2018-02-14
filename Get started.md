# Get started
orthogonalization: what to tune in order to try to achieve one effect? Each knob controls one factor 

For a superviseed system doing well: tune the knob for the system, make sure 4 things:
1. doing well on the training set, pass some acceptability assessment, might be comparably to human level performance -- a bigger network
2. dev set -- regulazation, bigger training set
3. test set -- a bigger dev set
4. performs well in the real world -- dev set / cost function

early stopping: difficult, simultaneously affect training and dev set

single number evaluation metric:
the standard way to combine precision and recall is something called an F1 score

satisfying and optimizing metric:
if you have N matrix that you care about it's sometimes reasonable to pick one of them to be optimizing. So you want to do as well as is possible on that one. And then N minus 1 to be satisficing

dev/test set:
workflow:
in machine learning is that you try a lot of ideas, train up different models on the training set, and then use the dev set to evaluate the different ideas and pick one. And, keep innovating to improve dev set performance until, finally, you have one clause that you're happy with that you then evaluate on your test set.

target:
setting up the dev set, as well as the validation metric, is really defining what target you want to aim at. And hopefully, by setting the dev set and the test set to the same distribution

size:
1. nowadays, we can have large percentage for train set, little for dev and test set, since the base number is huge
2. trend has been to use more data for training and less for dev and test, especially when you have a very large data sets. 
3. And the rule of thumb is really to try to set the dev set to big enough for its purpose, which helps you evaluate different ideas and pick this up from AOP better















