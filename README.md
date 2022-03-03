# Deep Learning Methods on EEG Recordings to Predict Epileptic Seizures

Epilepsy is a neurological disorder that disturbs the brain and causes abnormal brain activity. It results in unusual behavior, sensations, and in some cases loss of awareness.     

In this regard, if the seizures could be identified in their earlier stages then the patient can be provided appropriate care and treatment in time and preventing any severe damage to the patient as a whole.              

In this project, we try to detect epilepsy using the EEG Signal Recordings and classifying them using pre-trained CNN models between preictal and interictal classes. For this, we are advocating the use of the American Society for Epilepsy Dataset. The focus is on detecting the epilepsy pattern from the EEG recordings in an accurate and timely manner.     

The data was in .mat format which needs to be converted to images in order to implement CNN. Fourier Transform was done to convert them into images of frequency. Then resnet50, inception_resnetv2, and effcientnetb3 were implemented. The maximum accuracy achieved is 85% which was on efficientnetb3.          
