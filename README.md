Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-11-pso-optimization-system-for-cops
<br>
<h1></h1>

Development a PSO optimization system for continuous optimization problems (COPs). Conduct necessary system requirement analysis before implementing your system, to figure out the requirements of data structured and user interfaces for solving COP benchmarks. You are given a library (.dll) and a set of COP benchmarks to import a formatted COP to your code. The class lab will instruct you the use of the library to take advantages of accessing a COP benchmark. Notice that C# code snippet is specified in the formatted file to define the objective function. The library provides run-time C# compiling capability to generate a dynamic dll file., The compiled dll interacts with your application by providing the objective evaluation function of the problem.

The system should have basic yet friendly user interfaces for benchmark problem selections, PSO parameter settings, and stopping condition settings, etc. It is very helpful for knowing the solutions evolution of a 2D COP, which can be visualized in a 3D objective surface.

<strong>Continuous Optimization Problems: </strong>

CALab collects near half a hundred of real number optimization benchmarks. They are expressed in RTF files and .cop files. A general format of the optimization problem is the following:

<em>n</em>:dimension

A possible PSO or GA real number encoding:

<strong>x</strong>=<em>x x</em><sub>0 1 </sub><em>x<sub>n</sub></em><sub>−1</sub>;<em>l</em><em><sub>i </sub></em> <em>x<sub>i </sub></em><em>u i<sub>i</sub></em>; = 0,1, ,<em>n</em>−1 <em>x</em><em><sub>i </sub></em>:the real value of the th component<em>i</em>

<em>l<sub>i </sub></em>:the lower bound of <em>x</em><em><sub>i </sub></em><em>u<sub>i </sub></em>:the upper bound of ,<em>x l</em><em><sub>i i </sub></em> <em>u<sub>i</sub></em>, <em>i </em>min <em>f </em>(<strong>x</strong>)

Example:

Peak.rtf

Title: Peak function Source: MATLAB peak.m Problem:

min ( , )<em>f x y </em>= 3 1-( <em>x</em>)2 <em>e</em>− − +<em>x</em>2 (<em>y </em>1)2 −10 5<em>x </em>− <em>x</em>3 − <em>y</em>5 <em>e</em>− −<em>x y</em>2                   2 − 13<em>e</em>− + −(<em>x </em>1)2 <em>y</em>2

<ol>

 <li><em>st</em>. .</li>

</ol>

−4  <em>x y</em>,  4




            2           6<em>x</em>3)<em>e </em><em>x </em>(<em>y </em>1) +(− +2        34<em>x</em>2 −20<em>x</em>4 −20<em>xy</em>5)<em>e </em><em>x y </em>+ 2(<em>x</em>

 = <em>f   </em>  6     12<em>x                  </em>− − +2     2                                                                                    − −2   2        3 +1)<em>e</em>− + −(<em>x </em>1)2 <em>y</em>2 

(− +       −

−6(1+ <em>y</em>)(1− <em>x</em>)2 <em>e</em>− − +<em>x</em>2 (<em>y </em>1)2 +(4<em>xy</em>−20<em>x y</em>3 +50<em>y</em>4 −20<em>y</em>6)<em>e</em>− −<em>x y</em>2 2 + 2 <em>ye</em>− + −(<em>x </em>1)2 <em>y</em>2      

                                                                                       3

Optimal Value: -6.5511

(<em>x y</em>, ) =(0.2283, -1.6255)

Optimal Solution(s):




Peak.cop





