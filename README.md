# video-based-action-recognition

Action recognition is a challenging problem in computer vision and has various applications such as video surveillance, human-computer interaction, and sports analysis. To address some of these challenges, the extraction of features from the upper and lower halves of the human body using human body localization and optical flow information is performed. Two by Two streams of deep learning models are employed for classification. Two meta-streams are used to process different human body parts, while for each meta-stream, two sub-streams are used to handle different data modalities. The method achieves a notable accuracy of 92.86% on the UCF sports dataset.

The method involves:
Locating the human body using Human Body Detection and extracting upper and lower halves as major input features. 
Utilization of optical flow information from original movie as additional features. 
Application of two meta-streams to classify the two sets of data (upper and lower half). For each meta-stream, two modality-stream of deep learning models are used in procesing.
Combination of classification outcomes of the all streams to produce the final result. Approach enhances model's ability to handle erroneous visual information from partial occlusion of human body

This methodology and approach is proposed and implemented by NartayXD, Ahsan and me. We hope to further develop this work and idea.
