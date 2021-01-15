# Deep Image Feature Extractor
Deep Feature Extractor utilize the feature extraction layer from deep learning so then can be used as an input in other machine learning classifier.
You can change the architecture directly in the notebook by changinng the 'model' variable. Make sure to type the correct name of the model available by pytorch. 
You can also use your own model by creating the model just before defining the 'model' variable.
If you're planning on comparing the cnn and other machine learning performance, make sure that the model.state is identical in both cases.
The extracted features is named 'featuresfinal.csv'. You can also see the extracted feature by calling the variable 'featuresfinal'
