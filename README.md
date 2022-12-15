# Face Recognition using Eigenfaces

##  TEAM MEMBERS:

- Chandan Shrivastava - 2020101015

- Sankalp Bhat  - 2020112018

- Shreeya Singh - 2020102011

- Urvish Pujara - 2020101032

# Install dependencies
```bash
pip install -r requirements.txt
```
  
#  Goal of the project:

The primary goal of this project was to implement the method of Eigenfaces for face recognition by projecting the face images on the feature space (face space) which best represents the variations among distinct faces. We also implement Fischerfaces. This was done using Linear Discriminant Analysis. We have also compared the results of these two algorithms with another well-known method (LBPH).  

#  Repository Structure
All the data required are present in the repository, however if required they can be downloaded links mentioned in the dataset section of README.
1. [Dataset](/final_dataset/): Contains 4 folders i) at&t dataset ii)yaleB dataset iii)misc folder used for comparison iv) PinDown__faces-of-everyday-objects contains no-face images which gives appearance of face
2. [Eigenface_YaleB](/Eigenface_YaleB.ipynb): Contains entire implementation of eigenfaces on YaleB dataset along with test images classification
3. [Eigenface_AT&T](/Eigenface_AT_T.ipynb): Contains entire implementation of eigenfaces on AT&T dataset along with test images classification
4. [Fisherfaces](/Fisherfaces.ipynb): Contains entire implementation of fischerfaces on YaleB dataset along with test images classification
5. [Comparison](/Comparison.ipynb): Contains testing of eigenfaces by training on YaleB and testing for non-face images and mixiture of face,non-face images
6. [Inbuilt_LBPH](/Inbuilt_LBPH.ipynb): Contains testing of alternate method used from reference directly purely for comparison purpose
7. [Inbuilt_Eigenfaces](/Inbuilt_Eigenfaces.ipynb): Using an inbuilt function on yaleB dataset to check for accuracy comparison
8. [Report](/Report.pdf): Project report

# Dataset
Two different datasets have been used to obtain the face images
- the AT&T dataset: [Link](https://www.kaggle.com/kasikrit/att-database-of-faces)
- the Yale B dataset: [Link](http://vision.ucsd.edu/~iskwak/ExtYaleDatabase/ExtYaleB.html)
- No-Face dataset: A dataset of images without faces, sourced from pinterest. Uploaded in the Repository
- Additional miscellaneous images obtained from google
NOTE: All of them are available in the github repository itself. Preprocessing has been done on the YaleB dataset for more accurate results.