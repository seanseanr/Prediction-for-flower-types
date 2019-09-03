# Prediction-for-flower-types
Prediction of flower types in Kaggle. I just use the 3-layer CNN to train and predict and I get
about 75% of correctness. In the train process I tune the batch size to be 32 and add
GlobalAveragePool layer into the layer before last layer and that get better converging speed
and prevent training process crashing because of too many weights to calculate. Then I use
transfer learning by choose Inception model and train data with pre-trained Imagenet dataset
weights.
