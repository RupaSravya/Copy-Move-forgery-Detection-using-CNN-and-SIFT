# Copy-Move-forgery-Detection-using-CNN-and-SIFT
Image Forensics, Forgery Detection, CNN, Simple Linear Iterative Clustering, SIFT
Images play a crucial role\cite{1} in various fields like medicine, education, digital forensics, sports, research, surveillance, and news media.
They serve as primary sources of information. The accessibility of affordable and open-source image editing software such as Photoshop, Paint Shop, Photo-plus, GIMP, and Coral Draw has made it effortless to create manipulated images. 
These advanced tools have made it difficult to distinguish between an authentic image and an altered one with the naked eye. 
The process of creating manipulated images by altering original image data is known as digital image forgery. Detecting such forgery can be approached actively or passively.

Copy-move forgery involves duplicating and repositioning image segments, posing challenges for detection.
Traditional methods use key-point features or block-level alignment but struggle with complexity. 
Adaptive over-segmentation divides images into patches, reducing computational load for feature matching.


The proposed approach involves a synergistic integration of\cite{7} Convolutional Neural Networks (CNN) and Scale-Invariant Feature Transform (SIFT) for enhanced image analysis. The CNN captures complex spatial patterns and semantic features, enabling it to recognize objects and scenes effectively. Simultaneously, SIFT extracts distinctive key-points invariant to scale\cite{9}, rotation, and illumination, providing robust feature representations. The fusion occurs by employing SIFT features as complementary information to the CNN's predictions. During inference, SIFT key-points are detected and descriptors extracted from input images, which are then combined with CNN's feature maps before making final predictions. This synergy aims to improve recognition accuracy and resilience against variations\cite{14}. The approach not only harnesses CNN's deep learning capabilities but also leverages SIFT's stability in diverse conditions, creating a more robust and accurate image analysis pipeline.

OUTPUT:

![op tree](https://github.com/RupaSravya/Copy-Move-forgery-Detection-using-CNN-and-SIFT/assets/49145304/e1caf3ff-bdce-4cdf-ae9f-2e39307e49aa)


