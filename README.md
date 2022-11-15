# Lung and Colon Cancer Histopathological Images classification
 Final Project in CHHD304 Introducton to Precision Medicine

## Prerequisite
This project using CNN with keras and Tensorflow. So, This is library you need to install first
1. Tensorflow
2. Numpy
3. Pandas
4. Matplotlib
5. Seaborn
6. OpenCV
7. Scikit Learn
8. tqdm

## Dataset
This dataset contains 25,000 [histopathological images](https://en.wikipedia.org/wiki/Histopathology) with 5 classes. All images are 768 x 768 pixels in size and are in jpeg file format.  
The images were generated from an original sample of HIPAA compliant and validated sources, consisting of 750 total images of lung tissue (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas) and 500 total images of colon tissue (250 benign colon tissue and 250 colon adenocarcinomas) and augmented to 25,000 using the `Augmentor` package.  
There are five classes in the dataset, each with 5,000 images, being:
- Lung benign tissue
-   Lung adenocarcinoma
-   Lung squamous cell carcinoma
-   Colon adenocarcinoma
-   Colon benign tissue
</br>[Download dataset ](https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af)
