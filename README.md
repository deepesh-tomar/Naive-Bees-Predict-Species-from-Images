# Naive-Bees-Predict-Species-from-Images

# A supervised learning model trained on SVM(Support Vector Machine) to predict the species of bees from images

### Image preprocessing is done with hog(histogram or oriented gradients) to create features for each image on which model can be trained and learn

### Use of PCA{principle component analysis) for dimentionality reduction and reduce dimentions from 31K to 500

### Training of model on SVM from sklearn with decent accuracy 

### Calulating .predict_proba(probability) of prediction for each image for ROC (Receiver operating characteristic) and AUC (Area Under the Curve).
