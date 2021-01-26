## Bayesian classifier and Decision Tree

1. Consider a 3-class classification problem with 3 features: 2 of which are binary and 1 discrete with 4 values. 200 training examples are provided. In the table below, the statistics of these examples  are  provided.  Using  them,  construct  a  decision tree  of  depth  3,  i.e.  choose  two features  for  splitting  sequentially.  Use  the  decision  tree  to  compute  the  accuracy  on  the training set, i.e. how many of the200 training examples are classified correctly

2. Suppose you have been given only part of the above table, other rows are missing (X). Use a Naïve Bayes Classifier to make class label predictions for the feature values along those rows. Indicate the corresponding confidence values

3. Given  20  training  examples  with  2  features –both  continuous,  construct  the  best  decision stump (single split)withonly 2 leaf nodes.Choose the feature and also the threshold.Plotting the points on 2D plane may help you

4. Use  the  same  examples  as  above  to  construct  a Naïve Bayesian  Classifier  where  the  Class-conditional distributions are Normal (for each feature). Estimate the parameters of the normal distributions from the data (sample mean and sample variance). For which feature values isyour NBC least confident?

5. (i)  You  are  given  a  training  set  with  N  data-points  of  the  form  (xi,  yi,  wi),  where  xi  is  a  D-dimensional  vector,  the  label  yi  is  real-valued,  and  widenotes  the  weight.  You  are  now required to fit a linear regression model to this data, of the form y=a’x + b as usual. However, fitting errors are now weight-dependent, i.e. the loss should be more for points with higher 
weightage.  Find  the  linear  regression  model  in  this  situation,  starting  from  the  objective function and showing the necessary steps.                                            


5. (ii) Suppose you are given N datapoints (xi, yi) where xi is a D-dimensional vector and the label yi is real-valued. One again you are required to fit a linear regression model to this data, but the vector “a” should be as close to a given vector “v” as possible in terms of Euclidean distance. Find thelinear regression model in this situation, starting from the objective function and showing the necessary steps.                            
