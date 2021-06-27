# Rock Paper Scissors hand detector

This code was submitted as an image processing project done by me and 3 other students. It was made with tensorflow using convolutional neural network (CNN).
A webcam is needed to execute the 6th part of the code - *Playing against the AI with Webcam*.

___

## Dataset Used

The datasets used for training and testing can be downloaded here : 
- [Training set](https://storage.googleapis.com/download.tensorflow.org/data/rps.zip)
- [Testing set](https://storage.googleapis.com/download.tensorflow.org/data/rps-test-set.zip)

 Some images gesture found in both sets can be confusing/weird (e.g Rock made with the thumb up, Scissor using 3 fingers ...). I personnaly recommend not using the weird ones for better results.
 The images in the sets are in color, the program converts them in black & white before feeding them to the neural network to avoid biasis based on skin colors.
 
 ___
 
 ## Personnal Dataset
 
 Another dataset was made by ourselves to compare results with the online one. It also improves accuracy for our detector since the background in our dataset isn't perfectly white, the CNN must takes into account the background variations for the prediction. 
 
 ___

 In both case, data augmentation is performed to increase robustness of our predictor. We estimated an accuracy improvement of 5 to 10% from base CNN. 

Last part of our program is used to estimate the best parameters (number of neurons and optimizer) for our predictor.

 
 
