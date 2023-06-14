# video-based-action-recognition
Video-based action recognition is the task of recognizing human actions from videos and it is challenging due to variations in lighting, occlusion, and viewpoint. Here, an optical flow integrated two-by-two stream model for robust video-based action recognition is proposed. The method involves:
Locating the human body using Human Body Detection and extracting upper and lower halves as major input features. 
Utilization of optical flow information from original movie as additional features. 
Application of two meta-streams to classify the two sets of data (upper and lower half). For each meta-stream, two modality-stream of deep learning models are used in procesing.
Combination if classification outcomes of the all streams to produce the final result. Approach enhances model's ability to handle erroneous visual information from partial occlusion of human body

This methodology and approach is proposed and implemented by NartayXD and me. We hope to further develop this work and idea.
