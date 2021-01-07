# Image Classification Using Convolutional Neural Network

* The goal is to classify around 25k images of size **150x150** distributed under 6 categories.  
* **Class Categories:**  Buildings(Label 0),Forest(Label 1),Glacier(Label 2),Mountain(Label 3),Sea(Label 4),Street(Label 5).
* **CNN Architecture Used:** VGG16
* **Techniques Used:** Transfer learning And Data Augmentation. 
* **DataSource:** [Intel Image Classification](https://www.kaggle.com/puneet6060/intel-image-classification)


## Usage

```bash
Colab Notebook Image_Classification_CNN.ipynb
```

### Dataset
![Dataset](https://i.ibb.co/sy2bdXF/Dataset.png)
### Summary of transfer learning based VGG16 pre-trained model on imagenet
![CNN](https://i.ibb.co/HDy6kwL/Capture1.png)
![CNN](https://i.ibb.co/r6d1YRf/Capture2.png)
### Accuracy on training and validation Data on Base Model(Model without Data_Augmentation).
![CNN](https://i.ibb.co/MChmv69/Capture1.png)
### Training and Validation Performance Graphs of accuracy per epoch on Base Model(Model without Data_Augmentation).
![CNN](https://i.ibb.co/S7P23mS/Capture2.png)
### Training and Validation Performance Graphs of loss per epoch on Base Model(Model without Data_Augmentation).
![CNN](https://i.ibb.co/gMP0DZM/Capture3.png)
### Test Loss and Accuracy evalution of Base Model(Model without Data_Augmentation).
![CNN](https://i.ibb.co/DMS9vdy/Capture4.png)


### Accuracy on training and validation Data on Model after applying Data_Augmentation.
![CNN](https://i.ibb.co/Lpx4Rsr/Capture5.png)
### Training and Validation Performance Graphs of accuracy per epoch after applying Data_Augmentation.
![CNN](https://i.ibb.co/QYtXj6k/Capture6.png)
### Training and Validation Performance Graphs of loss per epoch after applying Data_Augmentation.
![CNN](https://i.ibb.co/09KXXqJ/Capture7.png)
### Test Loss and Accuracy evalution after applying Data_Augmentation.
![CNN](https://i.ibb.co/9W32kmP/Capture8.png)
### Confusion Matrix after applying Data_Augmentation.
![CNN](https://i.ibb.co/Qr73BVV/Capture9.png)


