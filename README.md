# LQG-CNN
Code for "Real-time Facial Expression Recognition via Quaternion Gabor Convolutional Neural Network", which have been submitted.
# Abstract
Real-time facial expression recognition (FER) has become a hot spot in computer vision. Convolutional neural networks (CNNs) are commonly employed in FER to extract features and predict emotions. However, CNNs struggle to balance performance and computation, which is crucial for real-time applications. Another challenge is the inadequate consideration of color information. When working with images, CNN models typically either treat the color image as three independent channels or convert it to grayscale, losing important information related to facial expressions. To this end, we propose a lightweight quaternion Gabor CNN (LQG-CNN) for real-time FER.  LQG-CNN encodes color images into quaternions, allowing it to naturally handle the interrelationships between color channels within a quaternion framework. Additionally, quaternion Gabor convolutional layers are introduced to capture spatial transformations, which require fewer parameters and offer faster inference speeds, making real-time FER feasible. Experiments on three datasets demonstrate that LQG-CNN achieves cost-efficient performance, outperforming other methods. Code will be available at https://github.com/jiangbeibe/LQG-CNN.
# LQG-CNN
![44e49bcc-0376-44bd-a85e-a6309c1d7c47](https://github.com/user-attachments/assets/d0411876-c9f0-4039-9a4a-95b142510d97)

# Results
![图片](https://github.com/user-attachments/assets/428b875b-4175-4dbf-8286-cef3d719caad)

If it's useful, please cite @article{zhou4936550real, title={Real-Time Facial Expression Recognition Via Quaternion Gabor Convolutional Neural Network}, author={Zhou, Yu and Guo, Liyuan and Jiang, Beibei and Wang, Bo and Jing, Kunlei}, journal={Available at SSRN 4936550}}
