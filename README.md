# Image_Classification_Using_CNN
Dataset: The Dogs vs. Cats dataset is a standard computer vision dataset that involves classifying photos as either containing a dog or cat
It was only effectively addressed in the last few years using deep learning convolutional neural networks. While the dataset is effectively solved, it can be used as the basis for learning and practicing how to develop, evaluate, and use convolutional deep learning neural networks for image classification
The **Dog Vs Cat** image classification dataset consists of 8005 images belonging to 2 classes for training images and 2023 images belonging to 2 classes for testing images 


1.   Class I = Dog
2.   Class II= Cat

* Prepare the dataset for the model
* Develop convolutional neural network model for classifying the images or Dog Vs cat
* Plot the change in accuracy per epochs
* Evaluate the model on the testing data
* Analyse the model summary
* Add Dropout to prevent overfitting and check its effect on accuracy
* Increasing the number of Hidden Layers check its effect on accuracy
* Manipulate the batch_size and epochs and check its effect on accuracy

![Alt Text](https://camo.githubusercontent.com/f0fe57a3540c293e21dcadff0cf5dedf3aaaea16509613822ee713fd40228a91/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313833382f312a6f4233533579484868766f75674a6b50587563386f672e676966)


- Dropout: used to deactive some neurons randomly to prevent overfitting
-  Early Stop: To prevent over fitting we will stop the learning after 10 epochs and val_loss value not decreased
- Learning Rate Reduction: We will reduce the learning rate when then accuracy not increase for 2 steps

- monitor: quantity to be monitored.
- factor: factor by which the learning rate will be reduced. new_lr = lr * factor
- patience: number of epochs with no improvement after which learning rate will be reduced.
- verbose: int. 0: quiet, 1: update messages.
- mode: one of {auto, min, max}. In min mode, lr will be reduced when the quantity monitored has stopped decreasing; in max mode it will be reduced when the quantity monitored -has stopped increasing; in auto mode, the direction is automatically inferred from the name of the monitored quantity.
- min_delta: threshold for measuring the new optimum, to only focus on significant changes.
- cooldown: number of epochs to wait before resuming normal operation after lr has been reduced.
- min_lr: lower bound on the learning rate.






Successfully developed a CNN model using transfer learning to achieve an accuracy of 98%.
