## Title of the Project
The primary goal of this project is to develop a robust and efficient deep learning model to assist in the automated classification of kidney abnormalities.
## About
<!--Detailed Description about the project-->
This project focuses on classifying kidney CT scan images into four distinct categories: Normal, Cyst, Tumor, and Stone using a deep learning model based on the VGG16 architecture. By leveraging transfer learning from the pre-trained VGG16 model, we aim to enhance feature extraction from the images and improve the model's classification accuracy.The dataset used in this project comprises CT images categorized into the four aforementioned classes. The model is trained using TensorFlow and Keras, with careful data preprocessing and augmentation to ensure high accuracy and generalization on unseen data.

## Features
<!--List the features of the project as shown below-->
  Accurate Kidney Classification
  
  Efficient Image Preprocessing
  
  High scalability.
  
  Comprehensive Performance Metrics
  
  Real-time Prediction


## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* Deep Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV, and Mediapipe for deep learning tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![vgg 16 arch](https://github.com/user-attachments/assets/b026b62f-5aa8-4a23-af0f-9dcf1ac56fc3)

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Stone

![377475052-5ad666b3-1ee1-49e0-97bc-a4f1816ae969](https://github.com/user-attachments/assets/d799dfad-af21-464a-8853-47f7f6ed83cb)

#### Output2 - tumor
![377475565-93e6ea53-1778-4adc-ba51-ea888824f62b](https://github.com/user-attachments/assets/cdeb37e9-2d4c-4218-b3a2-985764bf0c8e)

#### Output3 - cyst
![377475187-f4ae62af-3a65-43d0-9d5b-f309ce7fee41](https://github.com/user-attachments/assets/893417a0-8cdc-44e8-b2a9-71d6311ffbac)

#### Output4 - normal
![377475338-da7265eb-8ec3-48af-a7d0-392004d69093](https://github.com/user-attachments/assets/2bd687ed-6ad9-4802-beeb-5f0a0cf18981)


Detection Accuracy: 96.7%

## Results and Impact
<!--Give the results and impact as shown below-->
The project successfully classified kidney abnormalities (Normal, Cyst, Tumor, and Stone) using the VGG16 model, achieving high accuracy across all classes. The model demonstrated strong generalization with validation accuracy exceeding 99%, showing minimal overfitting. The confusion matrix and classification reports confirmed the model's ability to accurately detect abnormalities. This approach has the potential to significantly enhance diagnostic efficiency in medical imaging.

## Articles published / References


  1.Maqsood, F., Zhenfei, W., Ali, M.M. et al. Artificial Intelligence-Based Classification of CT Images Using a Hybrid SpinalZFNet. Interdiscip Sci Comput Life Sci (2024). https://doi.org/10.1007/s12539-024-00649-4

  2.Bingol H, Yildirim M, Yildirim K, Alatas B. 2023. Automatic classification of kidney CT images with relief based novel hybrid deep model. PeerJ Computer Science 9:e1717 https://doi.org/10.7717/peerj-cs.1717

  3.Asif, S., Qurrat-ul-Ain, Awais, M. et al. IR-CNN: Inception residual network for detecting kidney abnormalities from CT images. Netw Model Anal Health Inform Bioinforma 12, 35 (2023). https://doi.org/10.1007/s13721-023-00431-4

  4.Bhattacharjee A, Rabea S, Bhattacharjee A,Elkaeed EB, Murugan R, Selim HMRM,Sahu RK, Shazly GA and Salem Bekhit MM(2023) “A multi-class deep learning modelfor early lung cancer and chronic kidney disease detection using computed tomography images”. Front. Oncol. 13:1193746.doi: 10.3389/fonc.2023.1193746

  5.Bhandari, M.; Yogarajah, P.;Kavitha, M.S.; Condell, J. Exploring the Capabilities of a LightweightmCNN Model in Accurately Identifying Renal Abnormalities: Cysts, Stones, and Tumors, Using LIME and SHAP. Appl. Sci. 2023, 13, 3125. https://doi.org/10.3390/app13053125

  6.Alzu’bi, D., Abdullah, M., Hmeidi, I., AlAzab, R., Gharaibeh, M., El-Heis, M., Almotairi, K. H., Forestiero, A., Hussein, A. M., & Abualigah, L. (2022).” Kidney tumor detection and classification based on deep learning approaches: A new dataset in CT scans”. Article ID 3861161, 22 pages https://doi.org/10.1155/2022/3861161

  7.Islam, M.N., Hasan, M., Hossain, M.K. et al. Vision transformer and explainable transfer learning models for auto detection of kidney cyst, stone and tumor from CT-radiography. Sci Rep 12, 11440 (2022). https://doi.org/10.1038/s41598-022-15634-4





