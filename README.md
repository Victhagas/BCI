A simple classifier, using fastai and PyTorch, that differs the numbers 0 and 5 from MNIST dataset. You can see the original dataset on the Yann Lecun website, which is: http://yann.lecun.com/exdb/mnist/

Basically, this classifier uses the training and testing images, from MNIST Dataset, with a ~99% accuracy, to distinguish randoms 0s and 5s and tell us if they
really are it. To do so, I used the first fundamental equation from neural nets, x@weights + bias, and the Descend Gradient theory to make a model that learns over
the epochs set.

The initial part of the code is - aside from the importing and checking the Dataset - matrix (tensor) construction, and manipulation. So I stacked the training
and testing images into a 3rd rank tensor, then into a 2nd one. 

After this, there were a lot of Definitions to create the learning and other functions, such as initializing the parameters (weights, bias).

I tried to comment a lot to make things clearer, and I've structured the comments in Portuguese AND English.

Problems? Yes, they happened, as I was not used to working on machine learning projects before, there were a lot of things I needed to get help for,
for ex: DataLoader (which required me to create a previous Dataset), and the training structure.

100% sure that there are things that I didn't explain well or even did well (I'm sorry, it is my first project, and I promise to get better along the way).



BUILT WITH


-> Fastai, and those derivated from it, like Pytorch 
-> Tensorflow 


GETTING STARTED


-> If you are running on colab, you won't need any prerequisites at all, aside from getting the permission on the link (the first output, when you are importing 
will give it).

-> But, if you are on Colab, you can install fastai on your own machines with conda (highly recommended), as long as you're running Linux or Windows.
   (P.S.: Mac is not supported).

-> To install with pip, use: pip install fastai. If you install with pip, you should install PyTorch first by following the PyTorch installation instructions.


PREREQUISITES


-> As I am still learning a lot of things about Machine Learning, Deep Learning, and so on, you don't need any requirements to read and understand my code, aside from 
Having reasonable knowledge about Python and the will to learn (most important)!


CLONE THE REPO

-> git clone: https://github.com/Victhagas/Projects.git


INSTALLED PACKAGES


-> fastbook (by using: !pip install -Uqq fastbook)

IMPORTED LIBRARIES


-> Pandas
-> numpy
-> Matplotlib
-> Tensorflow


USAGE


-> If you really want the classifier, then you just need to run all the cells :)
-> But you are free to use the code in any way you want. Some examples are: Accessing easily and checking the MNIST dataset; seeing all or one specific image; 
   You can get all the desirable images and calculate the mean of thousands of handwritten images. Well, there aren't a lot of uses, but use your creativity :)
   

CONTRIBUTING

-> Contributions are what makes the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

CONTACT

-> Paulo Chagas - twitter: @victor_paulo00 - email: paulovictorchagas5@gmail.com - linkedin: https://www.linkedin.com/in/pvchagas/

Project Link: https://github.com/Victhagas/Projects

ACKNOWLEDGES

-> Special thanks to the CyberLab team, who proposed me this challenge!
