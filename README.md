# SA-C-GENDER-CLASSIFIER
# Algorithm
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface


## Program:
```python
/*
Program to implement Gender Classification
Developed by   : P.SUGANYA
RegisterNumber : 212220230049
*/
#install deepface
pip install deepface

#import packages
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read the image
img=cv2.imread('sugan.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

#Analyze gender
result=DeepFace.analyze(img,actions=['gender'])
result2=DeepFace.analyze(img,actions=['emotion'])

#print the gender
print("Gender : ",result['gender'])
```
</br>
</br>
</br>
</br>
</br>

## OUTPUT:


1. CODE :

![SA_NN_OUTPUT](https://user-images.githubusercontent.com/77089743/172676247-0d9e298e-ac60-493a-8cf3-27a68371ccaf.PNG)



2. DEMO VIDEO YOUTUBE LINK:
    
    https://youtu.be/BZ4oJZMed4w




