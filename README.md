# DeepDream
Implementing DeepDream in Keras.
DeepDream is an artistic image-modification technique that uses the representations learned ny convolutional neural networks. It was first released by Google in the summer of 2015, as an implementation written using the Caffe deep-learning library.
<p>The DeepDream algorithm is almost identical to the convnet filter-virtualization technique, consisiting of running a convnet in reverse: doing gradient descent on the input to the convnet in order to maximize the activation of a specific filter in an upper layer of the convnet.
  </p>
