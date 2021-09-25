About The Project


Simple classifier, using fastai and pytorch, that differs the numbers 0 and 5, from MNIST Dataset. You can see the original Dataset on Yann Lecun website, which is:
http://yann.lecun.com/exdb/mnist/

Basically, this classifier uses the training and testing images, from MNIST Dataset, with a ~99% accuracy, to distinguish randons 0s and 5s and tell us if they 
really are it. To do so, I used the first fundamental equation from neural nets, x@weights + bias, and the Descend Gradient theory to make a model that learns over
the epochs set.

The initial part of the code, is - aside from the importing and checking the Dataset - matrix (tensor) construction, and manipulation. So I stacked the training
and testing images into a 3rd rank tensor, then into a 2nd one. 

After this, there were a lot of Definitions, to create the learning and others functions, as initializing the parameters (weights, bias).

I tried to comment a lot, to make things clearer, and I've structured the comments in Portuguese AND English.

Problems? Yes, they happened, as I was not used to work on machine learning projects before, there were a lot of things I need to get help for,
for exemple: DataLoader (which required me to create a previous Dataset), and the training structure.

100% sure that there are things which I didn't explain well or even did well it (I'm sorry, it is my first project and I promise to get better along the way).



Built With


-> Fastai, and those derivated from it, like Pytorch 
-> Tensorflow 


Getting Started


-> If you are running on colab, you won't need any prerequisites at all, aside from getting the permission on the link (the first output, when you are importing 
   will give it).

-> Buuut, if you are on Colab, you can install fastai on your own machines with conda (highly recommended), as long as you're running Linux or Windows.
   (P.S.: Mac is not supported).

-> To install with pip, use: pip install fastai. If you install with pip, you should install PyTorch first by following the PyTorch installation instructions.


Prerequisites


-> As I am still learning a lot of things about Machine Learning, Deep Learning and so, you don't need any prerequistes to read and understand my code, aside from 
having a reasonable knowledge about Python and will to learn (most important)!


Clone the repo


-> git clone: https://github.com/Victhagas/Projects.git


Installed Packages


-> fastbook (by using: !pip install -Uqq fastbook)


Imported Libraries


-> Pandas
-> numpy
-> Matplotlib
-> Tensorflow


Usage


-> If you really want the classifier, then you just need to run all cells :)
-> But you are free to use the code in anyway you want. Some examples are: Acessing easily and checking the MNIST dataset; Seeing all or one specific image; 
   You can get all desirable images and calculate the mean of thousands of handwritings images. Well, there aren't a looot of uses, but use your criativity :)
   

Contributing


-> Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.


Contact

-> Paulo Chagas - twitter: @victor_paulo00 - email: paulovictorchagas5@gmail.com - linkedin: https://www.linkedin.com/in/pvchagas/

Project Link: https://github.com/Victhagas/Projects

Acknowledgements

-> Special thanks to the CyberLab team, whom gave me this challenge!
