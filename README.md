# Abandoned-Object-Detection-in-crowded-environment-using-MATLAB
We encompass techniques such as analyzing historical context, fusing evidence from multiple simple detectors, and using stable foreground image regions. These methods show promise in improving accuracy and robustness in real-time video surveillance scenarios, handling challenges like illumination changes, distractions, and occlusions. Successful implementation on datasets and real security systems validates the effectiveness of these methods in detecting unattended objects, although potential inaccuracies in input data are acknowledged as a limitation.
The abandoned bag detection employs a multifaceted approach involving Gaussian Mixture Model (GMM) for background modeling, blob analysis to identify potential objects, and Bag of Features (BoF) combined with SURF features for object representation. Vector quantization through k-means clustering is applied to generate feature descriptors. A Support Vector Machine (SVM) Classification model is trained on these features for accurate classification of abandoned bags. Evaluation of the model's performance is measured using a confusion matrix, providing insights into accuracy, precision, recall, and F1-score. This comprehensive methodology demonstrates robustness in identifying abandoned bags within complex environments.
