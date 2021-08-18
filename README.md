<h1> Adversarial Attacks on mnist dataset </h1>
Adversarial examples are inputs to machine learning models that an attacker has intentionally designed to cause the model to make a mistake; they’re like optical illusions for machines. <br>
Here I have attempeted to use Gradient tape from tensorflow which provides hooks that give the user control over what is or is not watched in a neural network. <br>
The basic idea was to do an Adversarial Attack on a CNN model so as to reduce the accuracy of out CNN model with affecting the grammar of image so much that it cannot be deteched by human eye.<br>
<br>
<h3> Dataset </h3>
The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.
It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. <br>

<h3>Gradient tapes</h3>
TensorFlow provides the tf.GradientTape API for automatic differentiation; that is, computing the gradient of a computation with respect to some inputs, usually tf.Variables. TensorFlow "records" relevant operations executed inside the context of a tf.GradientTape onto a "tape". TensorFlow then uses that tape to compute the gradients of a "recorded" computation using reverse mode differentiation.
<br>
Gradient tapes helps us to calculate differentials of every tensorflow operation. 
