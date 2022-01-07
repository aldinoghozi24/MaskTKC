# Klasifikasi Covid-19 Menggunakan Citra X-Ray Radiology

## Result Deployment to Heroku
link heroku : https://cov19-classification-261-235.herokuapp.com/

![Capture norm](https://user-images.githubusercontent.com/48962405/145395738-c1a80496-a5c5-40ec-af2c-8bc784d9baf7.PNG) ![Capture cov](https://user-images.githubusercontent.com/48962405/145395760-a2feec8a-d27a-4081-8cba-146c83b3050a.PNG)

## Deskripsi Dataset 

Dalam penyusunan project ini menggunakan 2 dataset dari sumber yang berbeda yang nantinya akan dikombinasikan; 
Dataset pertama berasal dari penelitian Tulin Otzurk, dkk yang berjudul [Automated detection of COVID-19 cases using deep neural networks with X-ray images](https://www.sciencedirect.com/science/article/abs/pii/S0010482520301621?via%3Dihub) pada tahun 2020
Dataset memiliki jumlah total sebanyak 1125 image yang terdiri atas 3 kelas dengan rincian :
1. Covid-19     : 125 images
2. No Findings  : 500 images
3. Pneumonia    : 500 images
dataset : https://github.com/muhammedtalo/COVID-19

Kemudian, dataset kedua yang digunakan dalam pembuatan project ini adalah COVID-19 Chest X-ray yang diakses melalui penelitian dari K. Ashif Iqbal, dkk [CoroNet: A deep neural network for detection and diagnosis of COVID-19 from chest x-ray images](https://www.sciencedirect.com/science/article/abs/pii/S0169260720314140?via%3Dihub) dengan tahun yang sama
Dataset terdiri atas 4 kelas dengan jumlah total 1638 image, dengan detail sebagai berikut : 
1. Covid                : 320 images 
2. Normal               : 445 images
3. Pneumonia Bacterial  : 449 images 
4. Pneumonia Viral      : 424 images
dataset : https://github.com/drkhan107/CoroNet

### Teknik Deep Learning yang digunakan

* Model dengan menggunakan algoritma ANN (Artificial Neural Network)
* Model dengan menggunakan algoritma CNN (Convolutional Neural Network)
* Model dengan menggunakan algoritma Transfer Learning Resnet50
* Model dengan menggunakan algoritma Transfer Learning DenseNet50
* Model dengan menggunakan algoritma InceptionV3
model dilatih dengan menggunakan google colabolatory. 

### Jurnal referensi 

* Jurnal referensi pada projek ini berjudul [Attention-based VGG-16 model for COVID-19 chest X-ray image classification](https://link.springer.com/article/10.1007/s10489-020-02055-x)
Sitaula, C., Hossain, M.B. Attention-based VGG-16 model for COVID-19 chest X-ray image classification. Appl Intell 51, 2850–2863 (2021). https://doi.org/10.1007/s10489-020-02055-x

### Cara Pengeksekusian Program

* Download file .ipynb 
* Buka di Notebook anda atau [google colabolatory](https://colab.research.google.com/) 

## Authors

Kontributor dalam projek ini yaitu :
* Ulfah Nur Oktaviana ulfanuroktaviana575@webmail.umm.ac.id
* Tiara Intana Sari tiaraintana@gmail.com

## Acknowledgments

Inspiration, code snippets, etc.
* [Covid19 Radiography Dataset](Attention-based VGG-16 model for COVID-19 chest X-ray image classification](https://link.springer.com/article/10.1007/s10489-020-02055-x)
* [CNN Tensorflow](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v1/examples/3_NeuralNetworks/convolutional_network.py)
* [DenseNet Documentation](https://keras.io/api/applications/densenet/)
* [Resnet Documentation](https://keras.io/api/applications/resnet/)
* [Keras Documentation of Transfer Learning Model](https://keras.io/api/applications/)
* [Data AUgmentation Using Tensorflow](https://www.tensorflow.org/tutorials/images/data_augmentation)

