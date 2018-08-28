# Image-encryption-and-decryption

This is a project that encrypts and decrypts the image by the concept of auto-encoders. This is very basic, yet effective, encoder-decoder model which does not more than 1 hidden layer for either.

The dataset I have used is MNIST dataset, and used very less dataset for training and the model is performing extremely well on the data. This is a Lossy-procedure.

The concept lies on the fact that we are encoding a 28x28 image(784 pixels) into 10x10 image(100 pixels) and updating the weights by mapping onto same 28x28 image(784 pixels)[DECODING].
We tend to optimise our model by minimizing the amount of loss in each iteration. Loss that is deployed is "mse" (Mean-Squared Error) that is a Reconstruction loss.


Auto-encoders have a different approach than how we process image. We process image as a matrix, in which each col and row has it value and significance.
but Auto encoders process it as a Vector of pixels. The spacial relation of a image is irrelevent when we make it a vector. Yet, the model giving such low loss with less dataset is highly commendable.







No. of epochs, Batch size is done by what fits best for my hardware, feel free to tweek it.
