# Classification of X-rays With and Without Fractures Using Feature Extraction and a Convolutional Neural Network
Bone fractures can occur in different regions of the body with varying severity and form depending on the type of injury. Some particular fractures, such as scapular and radial head elbow fractures, are difficult to spot, which could cause delays in diagnosis and, in effect, treatment. The goal of this study is to detect and classify different fractures in a variety of regions in the body making use of an extensive dataset of X-rays across all body regions. The data used is a compilation of three bone fracture datasets – Bone Break Classifier Dataset, bone_fracture, and fracture – made by Mohan Kumar, Abdelaziz Faramawy, and Harsha Arya respectively, with the datasets compiled into one named Bone Fracture Multi-Region X-ray Data by Madushani Rodrigo. These images were preprocessed in order to ensure the contrast between the bone and the fracture is visible. Masking was used to differenciate the bone from the background and fed into a convolutional neural network for classification. After training and validating, the network was able to classify the test set with 99.21% accuracy. This could help with the workflow of radiologists and reduce delays in diagnosis. This would be especially useful in emergency radiology for trauma patients.

*NOTE: Dataset was not able to be uploaded to GitHub due to the large volume of data. To access the dataset used, please see source 8.*

### References

[1] A. Pinto et al., “Traumatic fractures in adults: missed diagnosis on plain radiographs in the Emergency Department.,” PubMed, vol. 89, no. 1-S, pp. 111–123, Jan. 2018, doi: 10.23750/abm.v89i1-s.7015.

[2] L. Leapo, M. Uemura, M. C. Stahl, N. Patil, J. Shah, and T. Otteson, “Efficacy of X-ray in the diagnosis of pediatric nasal fracture,” International Journal of Pediatric Otorhinolaryngology, vol. 162, p. 111305, Sep. 2022, doi: 10.1016/j.ijporl.2022.111305.

[3] S. M. N. Fathima, R. Tamilselvi, and M. P. Beham, “XSITRAY: a database for the detection of osteoporosis condition,” Biomedical & Pharmacology Journal, vol. 12, no. 1, pp. 267–271, Mar. 2018, doi: 10.13005/bpj/1637.

[4] T. Aldhyani et al., “Diagnosis and detection of bone fracture in radiographic images using deep learning approaches,” Frontiers in Medicine, vol. 11, Jan. 2025, doi: 10.3389/fmed.2024.1506686.

[5] S. A. Shifani, G. Ramkumar, A. M. Clemencia, S. Maheswari, and S. Priyadharshini, “Identification of Bone Fragmentation in X-Ray Images using Contour Detection Algorithm,” International Journal of Innovative Technology and Exploring Engineering, vol. 8, no. 9, pp. 2121–2124, Jul. 2019, doi: 10.35940/ijitee.i7851.078919.

[6] G. Moon, S. Kim, W. Kim, Y. Kim, Y. Jeong, and H.-S. Choi, “Computer Aided Facial Bone Fracture Diagnosis (CA-FBFD) system based on object detection model,” IEEE Access, vol. 10, pp. 79061–79070, Jan. 2022, doi: 10.1109/access.2022.3192389.

[7] H. Sun et al., “Automated rib fracture detection on chest X-Ray using contrastive learning,” Journal of Digital Imaging, vol. 36, no. 5, pp. 2138–2147, Jul. 2023, doi: 10.1007/s10278-023-00868-z.

[8] M. Rodrigo, “Bone Fracture Multi-Region X-ray Data.” Apr. 23, 2024. [Kaggle]. Available: https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data/code?datasetId=4854718&sortBy=voteCount

[9] K. Team, “Keras documentation: Getting started with Keras.” https://keras.io/getting_started/?fbclid=IwZXh0bgNhZW0CMTAAAR03AkkHNjOxFrylW7yn13t16DVfrhnslyX0imXEq2MmeudQuBxiJIucfUU_aem_-TnzYXoH_avSpIaFuwgutg

[10] GeeksforGeeks, “Image Resizing using OpenCV | Python,” GeeksforGeeks, Aug. 09, 2024. https://www.geeksforgeeks.org/image-resizing-using-opencv-python/

[11] K. Team, “Keras documentation: The Sequential class.” https://keras.io/api/models/sequential/?fbclid=IwZXh0bgNhZW0CMTAAAR3wuKdq6c8bcKiWv87LYrGRcMUlKoR_wMPE1abBZm3movtEKgMswRI6Z58_aem_dLO5mfs0TeqLJ3NPYM4FmA

[12] K. Team, “Keras documentation: Image classification from scratch.” https://keras.io/examples/vision/image_classification_from_scratch/?fbclid=IwZXh0bgNhZW0CMTAAAR34fxQzL-nn2_l9p3Sq3KaZ7fF4IE4j0d_Vk0-PTa2v67gvY-Zd0gQdQm4_aem_EcJ_Rme6sjFT41hgTFFPdw#introduction

[13] A. Deshpande, “A Beginner’s Guide to understanding convolutional neural networks.” https://adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks/

[14] A. Deshpande, “A Beginner’s Guide to Understanding Convolutional Neural Networks Part 2.” https://adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks-Part-2/

[15] “Dense Layer vs convolutional layer - when to use them and how,” Data Science Stack Exchange. https://datascience.stackexchange.com/questions/85582/dense-layer-vs-convolutional-layer-when-to-use-them-and-how?fbclid=IwZXh0bgNhZW0CMTAAAR0-VcpYk1HcAoKfXsIu0LBbqctIhxeHkLS6G-e_C0bCJH3n1VKSwNtPJz0_aem_KU14QSDzQmYeTiiTESdb-A

[16] “When to use Dense, Conv1/2D, Dropout, Flatten, and all the other layers?,” Data Science Stack Exchange. https://datascience.stackexchange.com/questions/44124/when-to-use-dense-conv1-2d-dropout-flatten-and-all-the-other-layers?fbclid=IwZXh0bgNhZW0CMTAAAR1DNy3YMXkbj2js7Hh9VmMRsJYEO9f53EXdpBknX9pB4g5uZX42bjx0p8E_aem_LHTPt8TRuFTPrs4eEfay0A

[17] “Rescale parameter in data augmentation,” Data Science Stack Exchange. https://datascience.stackexchange.com/questions/92499/rescale-parameter-in-data-augmentation?fbclid=IwZXh0bgNhZW0CMTAAAR2hnVom07skHCX-TarLuK13x_oVkTweFUgQDtwKSPXlXLownQT7bwL6bWg_aem_7KlgZeF7SY-sxCqBpAkRyw

[18] “Data augmentation,” TensorFlow. https://www.tensorflow.org/tutorials/images/data_augmentation?fbclid=IwZXh0bgNhZW0CMTAAAR1DNy3YMXkbj2js7Hh9VmMRsJYEO9f53EXdpBknX9pB4g5uZX42bjx0p8E_aem_LHTPt8TRuFTPrs4eEfay0A

[19] “How do I determine the binary class predicted by a convolutional neural network on Keras?,” Stack Overflow. https://stackoverflow.com/questions/52018645/how-do-i-determine-the-binary-class-predicted-by-a-
convolutional-neural-network
[20] K. Team, “Keras documentation: Probabilistic losses.” https://keras.io/api/losses/probabilistic_losses/#binarycrossentropy-class
