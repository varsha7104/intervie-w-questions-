# TensorFlow
##  1) tensorflow definition 
A) Open source library developed by Google for numerical computation and machine learning
b) efficiently handle large scale machine learning and deep learning tasks
c) used to build and deploy ml models

## 2) tensorflow features
a) scalability:can start in one server and later use on other server without major code changes

b) portable : can run on various cpu and gpu 

c) tensor board : tensor board is powerful visualization tool for the visualizing 

d) flexibility: ml and dl models such as rnn ,cnn etc

## 3) explain  the concept of  tensors ?
tensors are fundamental data structures that represent and manipulate data 
term "tensors" refers to the mathematical concept that generalize the vector and matrices to higher dimensional data
it can store n dimensional data of single datatype 
##  4) difference between  tensor flow and pytorch ?
tensorflow is developed by google in 2015 whereas pytorch was developed by facebook meta ai in 2016 tensorflow uses more static graphs for computation whereas pytorch uses dynamic computational graph tensorflow is more used in production than pytorch Tensoflow learning tfx ,and torch serve onnx are production ready tools for tensor flow and pytorch respectively
## 5) types of tensors :
<img width="1366" height="768" alt="Screenshot (99)" src="https://github.com/user-attachments/assets/576fe366-c03e-4ad1-b92b-6553732c3a90" />

## 6) tensorflow execution model
Defining and executing computational graph to perform operations on tensors
## Graph Construction:

computation is represented as directed acyclic graph
nodes represent graph operations
It involves creating tensors and defining operations that compose a graph
## Graph Execution:

once a computation graph is defined we can perform those operation to obtain results of computation.
## 7) mention api used outside the tensorflow
A) TFLearn : Neural network creation and training quickly 

TensorLayer : dl and reinforcement learning library built on tensor flow
sonnet : for building complicated neural networks
## 8) tensor flow graph
 a) nodes : it represent  computation or  operations to be performed
 b) edges:they carry output of the operation
 c) operations: take i/p as tensor and o/p a tensor
 ## 9) tensorflow session:
  Tensorflow session is a class for running computational grpah It encapulsates graphs .It encapsulates the environment in whihc operations are executed 
  using a session you can execute operations in context
  ## 10) tensorflow board
  visual tool for inspecting and comprehending tensorflow runs and graphs 
  allows us to see and enhance graphs
  uses: visualize the model 
  monitor models
  histograms
  ## 11) tensorflow serving
  It is flexible high performance secing system developed by google 
  It focuses on production environment rather than research environment
  ## 12) place holder
 Serves as a input node in computational grpah They are used to feed input data int o graph during execution phase
 Dynamic data input as their value can be reassigned at runtime rather than being fixed during graph construction

## 13) embedding projector
Display high dimensional data
after input data is embedded in the high dimensional space by model it can be viewed
The model checkpoint file is read by the embedded projector

## 14) tensor flow variables
Mutuable state ful objects which can be store and manage the model parameters such as weight,bias in neural network
They allow the updates allowing in training iterations unlike tensors which are immutuable

