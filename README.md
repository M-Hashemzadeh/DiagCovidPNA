# DiagCovidPNA: Diagnosing and differentiating COVID-19, viral and bacterial pneumonia from chest X-ray images using a hybrid specialized deep learning approach

In this study, the DiagCovidPNA method is proposed to aid in diagnosing and differentiating COVID-19 disease and viral and bacterial pneumonia (PNA) from chest X-ray (CXR) images. The proposed method is founded on application-specific convolutional neural network (CNN) architectures. DiagCovidPNA is a four-class (i.e., COVID-19, normal lung, bacterial PNA, and viral PNA) diagnostic method that is offered in two different systems: 1) DiagCovidPNA and 2) Hybrid DiagCovidPNA. In the first system, a single CNN is used to classify the input images into four classes. In the second system, to differentiate bacterial and viral PNAs more accurately, the input images are classified into four classes using a combination of a three-class (i.e., COVID-19, normal lung, PNA) CNN-based classifier and a two-class (i.e., bacterial PNA, and viral PNA) CNN-based classifier. A comprehensive labeled database of CXR images is compiled for training and testing purposes using two sources of available images. In addition, the transfer learning method is employed to mitigate the issue of insufficient training data. Extensive experiments are conducted to evaluate and compare both systems to existing methods. According to the results, the diagnostic accuracy of DiagCovidPNA and Hybrid DiagCovidPNA is 95% and 97.50%, respectively. Consequently, Hybrid DiagCovidPNA improves accuracy by approximately 8% compared to other deep learning-based methods with a similar structure and by approximately 3% compared to a parallel transfer deep learning-based method. 


## Diagram of the proposed method:

![image](https://github.com/M-Hashemzadeh/DiagCovidPNA/assets/59253242/b4061fe7-a0fe-4e9e-8936-effa6d16cefd)


## Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:

V. Mohammadian Takaloo, M. Hashemzadeh, and J. Ghavidel Neycharan, "DiagCovidPNA: Diagnosing and differentiating COVID-19, viral and bacterial pneumonia from chest X-ray images using a hybrid specialized deep learning approach," Soft Computing (Under review), 2023.

2) Please do not distribute the database or source codes to others without the authorization from Dr. Mahdi Hashemzadeh (Corresponding author).

Author's Email: hashemzadeh[at]azaruniv.ac.ir (M. Hashemzadeh).

### *The use of code and dataset is not possible until the above article is published.
