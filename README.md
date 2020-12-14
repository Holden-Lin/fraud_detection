# fraud_detection
In  [this](https://www.kaggle.com/mlg-ulb/creditcardfraud) credit card fraud dataset where there are only **0.0017** positive examples, we have used typical supervised learning algorithm like logistic regression and deep learning algorithm of neural network to detect credit card frauds.
It turns out that simple tree models could have quite a good performance with F1 score of 86%.

We also try to upsample the positives to make the dataset more balanced. However, model performance after upsampling is not better than that before.Then we try shallow neural network and the recall improves while the precision deteriorate.

At last with anomaly detection, we easily achieve a recall score of 100% while the F1 is 71%. Anomaly detection is well suited in situations where positive training examples are not enough and there's no particular patterns of postive examples.

Actually this recall result is significantly higher than that of top Kaggle kernels.


