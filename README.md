# Sea Drones See Object Detection v2 on Edge Devices
## 1️⃣ Abstract:
This project focuses on developing an object detection system tailored for the SeaDronesSee dataset, which presents unique challenges such as diverse maritime environments, varying object scales, and complex backgrounds. Leveraging state-of-the-art deep learning models, the system is trained and optimized to achieve high accuracy. The trained model is then deployed on embedded hardware platforms, enabling real-time inference on resource-constrained edge devices. This approach supports robust and efficient object detection in marine surveillance and search-and-rescue operations, addressing practical deployment challenges in embedded systems.

### Key Features:
- YOLOv8-based model optimized for embedded real-time inference
- Custom data labeling and annotation to improve dataset quality and model training
- Deployed via TensorFlow Lite Micro on resource-limited devices
- Weighted non-maximum suppression to reduce false positives
- Multi-class detection with high accuracy (mAP metrics)
- Efficient prediction with measured FPS performance

## 2️⃣ Technologies Used:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)	
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

## 3️⃣ Dataset:
[SeaDronesSee](https://cloud.cs.uni-tuebingen.de/index.php/s/ZZxX65FGnQ8zjBP) is a large-scale, publicly available dataset designed for object detection and tracking in maritime environments using drone footage. It features a diverse collection of annotated videos and images capturing various objects such as boats, swimmers, life jackets, and buoys in challenging conditions including varying weather, lighting, and sea states.
- Train set: 8,930 images
- Test set: 3,750 images
- Valid set: 200 images (low costom for edge devices)
![image](https://github.com/user-attachments/assets/57db469e-9550-44ac-9e1f-8f98515b34fc)

## 4️⃣ Results:
1. **Model Training:**  
   Achieved high detection performance with a final mAP@0.5 of 87.7% after re-training and optimizing the YOLOv8 model.  
   ![image](https://github.com/user-attachments/assets/19cda869-b89f-4636-9e01-cd4d1d7b7298)
   ![image](https://github.com/user-attachments/assets/4ef1cc75-82c1-4faa-b2c4-375bc945ec4b)
3. **Deployment on Raspberry Pi Zero 2W:**  
   *(On-going — system integration and testing in progress)*
