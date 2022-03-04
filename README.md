# Brain-Tumor-Classification
<b> What is a brain tumor?</b>

A brain tumor is a collection or mass of abnormal cells in your brain. which surrounds your brain is very tough. Any growth within such a confined space can cause problems. Brain tumors can be malignant (malignant) or benign (benign). When benign or malignant tumors grow, they can cause an increase in pressure inside the skull. This can cause brain damage and be life-threatening.

<b> The importance of this research.</b>

Early detection and classification of brain tumors is an important area of research in medical imaging and therefore helps to choose the most convenient treatment to save the lives of patients.

<b> Dataset: </b>
1) The three types of tumors examined in this case study do not differ very much in terms of absorption levels (gray level in pixels). Consequently, the shape of the tumors will play an important role in its classification. The dataset used for this work is available at the following link.
https://figshare.com/articles/brain_tumour_dataset/1512427 .
Dataset Consists of 3064 T1 Weighted contrast-enhanced images from 233 patients with three kinds of a brain tumour

2) The 2nd dataset contains 3264 images of human brain MRI images which are classified into 4 classes:

   => glioma
   
   =>meningioma
   
   =>no tumor
   
   =>pituitary
   
 <b> Data Pre-processing. </b>
 
Crop only the part of the image that contains the brain (this is the most important part of the image): Crop technology is used to find the extreme top, bottom, left and right points of the brain using OpenCV.
 
![image](https://user-images.githubusercontent.com/91358909/140873232-4a933a7b-64cb-4bfb-a898-41b35ac464eb.png)

The objective of this case study is to develop the expert model through Deep-Learning algorithms to effectively classify the type of brain tumors.
 
