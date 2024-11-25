# OCTimageClassifier
I used a pre-trained resnet 18 model and extended it by training an additional layer that mapped 512 inputs to 2 outputs
The two outputs corresponded to classifying the image as either normal or an eye with an Epiretinal Membrane
The input images had to be resized to 224 by 224 due to the requirements of the resnet model
After 30 epochs of training, 13 minutes, the model achieved an accuracy of 94% on test data, consisting of about 100 examples
