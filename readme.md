# Malaria Detection and Classification using Deep Learning

This project focuses on developing a deep learning model to detect and classify malaria-infected human blood smears using the EfficientDet architecture. The dataset contains six classes with different cell types, and for each image, the annotation data is provided, which includes bounding box coordinates and class for each cell.

The project demonstrates the use of EfficientDet, a state-of-the-art architecture, and specifically the BiFPN layer for multi-scale feature fusion, in cell detection and classification. To handle the large class imbalances, the Focal Loss function was used, and the model was trained on 80% of the dataset while using the remaining 20% for validation.

Although the model did an excellent job of locating cells, the classification results were quoted as "worthless". Despite being state-of-the-art in many contexts, EfficientDet did not perform well in this use case owing to the common pattern in cell shapes. Nevertheless, the model's results are end-to-end and provide an improvement in comparison to the conventional models available.

This project aims to provide insights into the challenges involved in using deep learning models for detecting and classifying cells in the medical domain, and showcases the EfficientDet architecture as an alternative approach to conventional methods.

# References

- Tan, M., & Le, Q. V. (2020). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. arXiv preprint arXiv:1905.11946.
- Tan, M., Pang, R., & Le, Q. V. (2020). EfficientDet: Scalable and Efficient Object Detection. arXiv preprint arXiv:1911.09070.
- Lin, T. Y., Goyal, P., Girshick, R., He, K., & Dollár, P. (2018). Focal Loss for Dense Object Detection. arXiv preprint arXiv:1708.02002.
- Sandler, M., Howard, A., Zhu, M., Zhmoginov, A., & Chen, L. C. (2019). MobileNetV2: Inverted residuals and linear bottlenecks. arXiv preprint arXiv:1801.04381.

# Contact me

- Email: mohamad-mehdi@live.com
- LinkedIn: https://www.linkedin.com/in/m3di/