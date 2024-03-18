

<center><h1> Spark ML - Click Prediction </h1></center>

----

An Advertising company delivers more than 3 Billion clicks per month to its advertisers delivering 4.5 Million monthly sales events. 

It buys space on the Publishers site and then shows an advertisement about the Advertiser at that space. The advertiser pays the network for every conversion from the clicks. The network in turns pays to the publisher after keeping it's commission. The company wants to leverage the machine learning to improve the conversions for its customers.

So, in this notebook we will build a classification model to predict whether a particular advertisement will be clicked or not.

----

So for this notebook, we have divided the dataset into 3 different parts:
   * **`TRAIN`** - It has 1400000 Rows which will be used to train the model.
   * **`VALIDATION`** - It has 350000 Rows which will be used to evaluate the model.
   * **`TEST`** - It has 350000 Rows on which we will test our final model.
