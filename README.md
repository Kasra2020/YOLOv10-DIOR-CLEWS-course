# This repository serves only as the supportive material for the lecture entitled "Deep Learning Architectures - Theory and Applications in Earth Observation", given at Univeristy of Potsdam on July 7th, 2025. The lecture is part of a lecture series within the "Climate, Earth, Water, Sustainability (CLEWS)" course organized by Johan Rockström et. al.

- The YOLO model is implemented based on the paper "Wang, Ao, et al. "Yolov10: Real-time end-to-end object detection." Advances in Neural Information Processing Systems 37 (2024): 107984-108011". 

- The dataset utilized in this course is a subset of DIOR, sourced from "Li, Ke, et al. "Object detection in optical remote sensing images: A survey and a new benchmark." ISPRS journal of photogrammetry and remote sensing 159 (2020): 296-307".

Please note that the purpose of this notebook is purely educational. Due to time and computational constraints, we only use a subset of DIOR data: 139 images containing 1,232 instances. Therefore, our goal is not to develop or train the most accurate model. The model's low accuracy is due to the limited amount of data used to train the YOLOv10 model from scratch. Consequently, the results are suboptimal. However, performance improves slightly when fine-tuning a pretrained model with similar data.
