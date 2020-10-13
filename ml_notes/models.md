# Notes on Models


1. When you start training a model, don't add saving the model to the end of your file or notebook, if a bug gets introduced along the way after training, you might end up retraining your model. While if you save it immediately after training, you can forget about running it again and just used that saved model.
2. Have a separate directory for models and give them useful names. For example:
	- Bad practice: model1.pkl, model2.pkl, ...
	- Good practice: k-means_30clusters_JAN31.pkl, ... 
