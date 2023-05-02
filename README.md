Download Link: https://assignmentchef.com/product/solved-comp590-homework-5-convolutional-neural-networks
<br>
In this assignment you will practice with training Convolutional Neural Networks for digits classification tasks.

<strong>Setup </strong>

You can work on the assignment on google <u>​</u><a href="https://colab.research.google.com/notebooks/intro.ipynb">colab</a>​.

<strong>Pytorch neural network tutorial </strong>

<a href="https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html#sphx-glr-beginner-blitz-neural-networks-tutorial-py">https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html#sphx-glr-beginn </a><a href="https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html#sphx-glr-beginner-blitz-neural-networks-tutorial-py">er-blitz-neural-networks-tutorial-py</a>

<h1>1.  Filling in the training code</h1>

The dataloader and network architecture classes are all given to you. To train a deep neural network, you iterate through the whole training dataset multiple times (called epochs). At each step of training,

<ol>

 <li>extract a mini-batch from the training dataset and give it to the network;</li>

 <li>compute the loss between the output from the network and the groundtruth label; 3. compute the gradients of network weights with respect to the loss;</li>

 <li>update the weights.</li>

</ol>




<h1>2.  Answer questions</h1>

<ol>

 <li>How many layers are there in the neural network?</li>

 <li>How many features are there at each layer?</li>

 <li>What is the loss function? How does it penalize wrongly classified labels?</li>

 <li>If we change the input image size from 28×28 to 32×32, how should we modify the fc1() layer?</li>

</ol>