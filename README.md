# CNN for MIT-BIH
In this notebook I predict different arrhythmia on the ECG. An Electro Cardio Gram (ECG) is a simple test that can can be used to check your heart rhythm and electrical activity. The dataset is composed of the heartbeat signals deerived from the MIT-BIH Arrhythmia Dataset which contains 48 half-hour excerpts of two-channel ECG ambulatory recordings.Out of which 23 were randomnly selected from the patients and remaining 25 were chosen to include less common but clinically significant arrhythmias that would not be well-represented in a small random sample.

Initial dataset was biased therefore I employed resampling of dataset using upsampling with repetition. Apart from this One-Hot Encoding was also used in the process of categorisation of dataset. Sequential model was used for CNN Model training. Model consists of One Convolutional Block and One Output Block. Convolutional Block contains three Convolutional Layers with a Normalisation and MaxPooling Layer. Relu Activation functions were used along with Softmax for final output layer.

I achieved a total accuracy of about 98% and also plotted classification matrix with the f1 score, precision, recall and accuracy.
