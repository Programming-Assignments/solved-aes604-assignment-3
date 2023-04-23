Download Link: https://assignmentchef.com/product/solved-aes604-assignment-3
<br>



<h1>Questions</h1>




<ol>

 <li> The labels in a d-dimensional hypercube use <em>d </em>bits. Fixing any <em>k </em>of these bits, prove that the nodes whose labels differ in the remaining <em>d − k </em>bit positions form a (<em>d − k</em>)- dimensional subcube. For this, prove that (a) each such node has exactly (<em>d − k</em>) neighbors at Hamming distance of 1 (Hamming distance between two binary numbers is the number of bit position that they differ), and (b) this subcube is composed of 2<sup>(<em>d−k</em>)</sup> nodes.</li>

</ol>




<ol start="2">

 <li> A mesh of trees is a network that imposes a tree interconnection on a grid of processing nodes. A <em>√p X√p </em>mesh of trees is constructed as follows. Starting with a <em>√p X√p </em>grid, a complete binary tree is imposed on each row of the grid.  Then a complete binary tree is imposed on each column of the grid. Figure 2.36 illustrates the construction of a 4 x 4 mesh of trees. Assume that the nodes at intermediate levels are switching nodes. Determine the bisection width, diameter, and total number of switching nodes in a <em>√p X√p </em>mesh of trees (only calculate the order, in terms of big-Oh notation).</li>

</ol>




<ol start="3">

 <li><strong><em>OpenMP</em></strong> <strong><em>Programming</em></strong></li>

</ol>

(a)  Write a shared memory OpenMP program on Fox server to multiply two n-by-n matrices using p processors with 1&lt;= p &lt;=12. Fill up the matrices with some constant values so that it would be easier for you to verify the resulting matrix for correctness.




(b)  Prepare a speedup plot (T<sub>s</sub>/T<sub>p</sub>) or a table with varying n and vary number of processes in the available range. Use pure sequential time with three nested loop for T<sub>s </sub>(see below).




<em>Hint:</em> You may implement the sequential code in the same program and time it, followed parallel code and time that, and calculate the speedup.  Experiment and choose sufficiently large n for a reasonable speedup.  Larger n may result in better speedup.




/* matrix-matrix product loop */

for (i = 0; i &lt; dim; i++)

for (j = 0; i &lt; dim; j++)

for (k = 0; k &lt; dim; k++)

c[i][j] += a[i][k] * b[k][j];


