Download Link: https://assignmentchef.com/product/solved-geneticalgorithms-assignment4-back-propagation-neural-networks
<br>
<strong>Implement “Back propagation Neural Networks” </strong><sub> </sub>

In this assignment, ​ ​you are asked to write two programs. The first one implements the back propagation algorithm and the second one implements the feed forward.

In both assignments, you will need to read the input (x vector) and the output (y vector) from a file. Below is the structure of the input file:

<ul>

 <li>First line: M, L, N where M is number of Input Nodes, L is number of Hidden Nodes and N is number of Output Nodes</li>

 <li>Second line: K, the number of training examples, each line has length M+N values, first M values are X vector and last N values are output values.</li>

 <li>K lines follow as described</li>

</ul>

An example of input file (just for clarification not to be used):

3 2 2

3

1 1 1.5                2  2

-1 2.25 0.5 
-0.5 1.2

1 1 1                   1   2

<strong>Above is a file that describes:</strong>

<ul>

 <li>Network with 3 input nodes, 2 hidden and 2 output</li>

 <li>Training is 3 examples</li>

 <li>Second example has training example X [1 1 1.5] and output vector [2 2]</li>

</ul>

<strong>Deliverables of the first program: </strong>

<ul>

 <li>After reading the input file, you will do <strong><u>a normalization step</u></strong>​ on the input features.</li>

 <li>Normalization is done by computing, for each numeric x-data column value v, v’ = (v – mean) / std dev. This technique is sometimes called Gaussian normalization.</li>

</ul>




For example, the mean of the first column = (30 + 36 + 52 + 42) / 4 = 160 / 4 = 40.0. The standard deviation of the first column = sqrt((30-40)^2 + (36-40)^2 + (52-40)^2 + (42-40)^2) / 4) = sqrt((100 + 16 + 144 + 4) /

<ul>

 <li>= sqrt(66.0) = 8.12.</li>

</ul>




So the normalized value for an input of  value 30 = (30 –

40.0) / 8.12 = -1.23.




<ul>

 <li>you will perform back propagation algorithm, use dr. Notes as reference. (The algorithm should stop after reaching an acceptable MSE, or after running for a number of iterations, let’s say 500 iterations.)</li>

 <li>After finishing the 500 iterations, or reaching an acceptable MSE print that MSE on the screen and save your final weights to a file.</li>

</ul>

<strong>Deliverables of the second program:  </strong>

<ul>

 <li>After reading the input file, you will perform feed forward algorithm on the input data using the best weights you have calculated in the first program. Print the MSE.</li>

</ul>

<strong>Note: </strong>we will give you the input file in the discussion, but as​  mentioned before it will have the same structure as the input file of the first program.

<strong>Notes: </strong><sub> </sub>

<ul>

 <li>Groups are 3 members, from same lab</li>

 <li>Code should be well documented, and each team member is responsible for every line of code</li>

 <li>Code with <strong>static structure </strong>​ for network may not be marked​</li>

</ul>

(E.g. we must be able to try different network structures)