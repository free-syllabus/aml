## Introduction to Neural Networks

### Required Study Materials

1. **[Neural Networks Pt. 1 - Inside the Black Box](https://www.youtube.com/watch?v=CqOfi41LfDw)** (video:19min) by StatQuest
2. **[Neural Networks Pt. 2 - Backpropagation Main Ideas](https://www.youtube.com/watch?v=IN2XmBhILt4)** (video:18min) by StatQuest 
3. **[Neural Networks Pt. 3 - ReLU In Action](https://www.youtube.com/watch?v=68BZ5f7P94E)** (video:9min) by StatQuest 
4. **[Neural Networks Pt. 4 - Multiple Inputs and Outputs](https://www.youtube.com/watch?v=83LYR-1IcjA)** (video:14min) by StatQuest 

## Alternative Study Material
1. **[Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)** (video:50min) by 3Blue1Brown  <br>
Take a look at the first three parts of the playlist.

### Activities

* Logical operators using simple neural network [15 minutes]
  * [teacher] This task is suitable also before any proposed video
  * Create single linear combination (naive neuron without activation fn) with two inputs (0/1) where response "TRUE" is > 0 and "FALSE" is <= 0
  * First task is to create weights for AND and OR
  * Second task is to create weights for XOR
  * [teacher] Create graph with AND/OR/XOR and explain linearity issue
  * Explain activation function
* Manual backprogration to solve system of linear equations
  * Propose neural network architecture (single hidden layer is enough)
  * User relu as activation function
  * [teacher] Be aware of relu limitation with negative numbers
  * [teacher] Be aware of overfitting when training on single example
  * [teacher] Note that "deravition" is used to determine the direction of what to do with weights
  * First set of equations is 2a+3b=6 and 4a+7b=11
  * Use 2-3 round of backpropagation in order to improve random weights
  * Second set of equations are 3a-b=5 and 1a+2b=4
  * Use 1 round of backpropagation to see if we can closer to real results
  * Check new weights with first set of equations
* [advanced] Create NN architecture for specific equation
  * Create equations for solving system of 2 equations with 2 variables
  * [teacher] Be aware that you will have to work with multiply/division
   
* MNIST ?

### Reasoning

* @todo
