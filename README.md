# ISIC-2018-Skin-Lesion-Classification

The International Skin Imaging Collaboration hosted a dataset of containing images of seven different types of skin lesions (https://challenge2018.isic-archive.com). For the past three years they have hosted a competition to have people and teams from all across the globe create algorithms to classify different types of skin lesions, segment lesions, and determine distinct atributes. 

In this repository, I show my process for classifying different skin lesions. The final result was approximately 94% accuracy using Balanced Multiclass Accuracy as my scoring metric which was the metric of the competition. This result was calculated by holding out 20% (~2,000 images) of the training data as the competition did not release the ground truth for their validation set. 

This approach has been heavily influenced by the Fast.ai library and their course which can be found here: https://course.fast.ai 
A special thanks to Jeremy Howard and Rachel Thomas for their contributions in the community.
