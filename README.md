## Investigating the viability of detecting rooftop solar photovoltaics via convolutional neural networks using remote sensing images
This repository contains the training and testing notebooks for a research paper exploring CNNs' applicability in photovoltaic detection. The paper explores the viability of using CNNs in accurately detecting solar panels in real-world use cases. In the study, we fine-tuned a Faster R-CNN architecture on a dataset prepared by obtaining remote sensing images from Google Earth Engine and IGN and creating masks via a crowdsourced initiative ([Learn more](https://zenodo.org/record/7358126)). 

We, then, evaluated the fine-tuned model on a manually prepared dataset with diverse spatial resolutions and settings obtained via Google Maps to obtain more thorough and realistic metrics to finally conclude that the generalizability of the trained model is not good enough to be practically applicable. This work provides a foundation for future research on practically applicable neural networks for photovoltaic detection and suggests that a more practically viable photovoltaic detection system may involve more complex architectures like ViTs working with CNNs.

Link to the dataset used for training the model: https://zenodo.org/record/7358126 \
Link to the manually-created dataset used for testing the model: [test_data.zip](https://github.com/bharathraj-v/pv-detection/blob/main/test_data.zip). Source: Google Maps

**Paper Link**: [paper.pdf](https://github.com/bharathraj-v/pv-detection/blob/main/paper.pdf)\
**Status**: Published. [https://ieeexplore.ieee.org/document/10490316](https://ieeexplore.ieee.org/document/10490316) \
**Authors**: [Bharath Raj](https://www.linkedin.com/in/bharathraj-v/), [Dr. Prakash PS](https://www.linkedin.com/in/prakash2102/)
