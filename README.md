#U-Net Nuclei Segmentation
Overview
This project implements a U-Net-based architecture for nuclei segmentation in microscopy images. The primary goal is to accurately identify and segment nuclei from images to aid in biomedical research and analysis.

Features
U-Net Architecture: A fully convolutional neural network designed for biomedical image segmentation.
Accurate Segmentation: Achieves high precision and recall in segmenting nuclei from complex backgrounds.
Custom Dataset Support: Easily adapt the pipeline to new datasets.

Getting Started
i have used google collab here.
python 3.11collabc
tensorflow 2.17

Dataset
Use the Kaggle Nuclei Segmentation Dataset or your own microscopy dataset.
https://www.kaggle.com/code/paultimothymooney/identification-and-segmentation-of-nuclei-in-cells/input
Place images in the data/images/ directory and corresponding masks in data/masks/.

Model Architecture
The U-Net model consists of:
Contracting Path: Encodes the input image with successive convolutions and max-pooling layers.
Bottleneck: Bridges the encoder and decoder.
Expanding Path: Decodes the feature map back to the original image size with up-sampling and skip connections.

Results
![image](https://github.com/user-attachments/assets/5df63382-b243-4a18-9983-f6d39084a343)

References
Original U-Net Paper https://arxiv.org/pdf/1505.04597v1
