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
