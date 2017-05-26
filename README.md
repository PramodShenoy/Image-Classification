# Image-Classification
## Classifying images from the CIFAR-10 dataset<br>
The dataset is broken into batches to prevent your machine from running out of memory.  The CIFAR-10 dataset consists of 5 batches, named `data_batch_1`, `data_batch_2`, etc.. Each batch contains the labels and images that are one of the following:
* airplane
* automobile
* bird
* cat
* deer
* dog
* frog
* horse
* ship
* truck<br>
Here's a link to the [CIFAR webite](https://www.cs.toronto.edu/~kriz/cifar.html)

## Dependencies
``pip install -r requirements.txt``
## Usage and Accuracy
* Run the jupyter notebook from terminal using ``jupyter notebook`` command
* The accuracy obtained is around 67% whihc is around 7 times better than random guessing 
* Training takes a lot of time and using a GPU is recommended
### Fork the repo to improve accuracy
