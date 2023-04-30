Download Link: https://assignmentchef.com/product/solved-cs236781-deep-learning-on-computational-accelerators-homework-assignment-2
<br>
<h2><a id="user-content-introduction" class="anchor" href="https://github.com/BarakGahtan/Deep-Learning-HW2#introduction" aria-hidden="true"></a>Introduction</h2>

In this assignment we’ll create a from-scratch implementation of two fundemental deep learning concepts: the backpropagation algorithm and stochastic gradient descent-based optimizers. Following that we will focus on convolutional networks. We’ll use PyTorch to create our own network architectures and train them using GPUs on the course servers, and we’ll conduct architecture experiments to determine the the effects of different architectural decisions on the performance of deep networks.

<h2><a id="user-content-general-guidelines" class="anchor" href="https://github.com/BarakGahtan/Deep-Learning-HW2#general-guidelines" aria-hidden="true"></a>General Guidelines</h2>

<ul>

 <li>Please read the <a href="https://vistalab-technion.github.io/cs236781/assignments/getting-started" rel="nofollow">getting started page</a> on the course website. It explains how to <strong>setup, run and submit</strong> the assignment.</li>

 <li>Please read the <a href="https://vistalab-technion.github.io/cs236781/assignments/hpc-servers" rel="nofollow">course servers usage guide</a>. It explains how to use and run your code on the course servers to benefit from training with GPUs.</li>

 <li>The text and code cells in these notebooks are intended to guide you through the assignment and help you verify your solutions. The notebooks <strong>do not need to be edited</strong> at all (unless you wish to play around). The only exception is to fill your name(s) in the above cell before submission. Please do not remove sections or change the order of any cells.</li>

 <li>All your code (and even answers to questions) should be written in the files within the python package corresponding the assignment number (<code>hw1</code>, <code>hw2</code>, etc). You can of course use any editor or IDE to work on these files.</li>

</ul>

<h2><a id="user-content-contents" class="anchor" href="https://github.com/BarakGahtan/Deep-Learning-HW2#contents" aria-hidden="true"></a>Contents</h2>

<ul>

 <li>Part1: Backpropagation

  <ul>

   <li>Comparison with PyTorch</li>

   <li>Block Implementations</li>

   <li>Building Models</li>

  </ul></li>

 <li>Part 2: Optimization and Training:

  <ul>

   <li>Implementing Optimization Algorithms</li>

   <li>Vanilla SGD with Regularization</li>

   <li>Training</li>

   <li>Momentum</li>

   <li>RMSProp</li>

   <li>Dropout Regularization</li>

   <li>Questions</li>

  </ul></li>

 <li>Part 3: Convolutional Architectures

  <ul>

   <li>Convolutional layers and networks</li>

   <li>Building convolutional networks with PyTorch</li>

   <li>Experimenting with model architectures</li>

   <li>Questions</li>

  </ul></li>

</ul>