Download Link: https://assignmentchef.com/product/solved-cs575-assignment-6
<br>
<strong><u>Objective: </u></strong>

<ul>

 <li>Understand the backtracking algorithms</li>

 <li>Enhance the concept of Intractability and the theory of NP.</li>

</ul>

<ol>

 <li>Given the following sum of subset problem. S=10, and the integers are 3, 9, 2, 6, 7.

  <ol>

   <li> If no pruning is made on the whole state space tree. How many nodes does it contain?</li>

   <li> Apply the backtracking algorithm. Whenever you find that a node is not promising backtrack. How many nodes does your tree contain? Draw the pruned state space tree.</li>

  </ol></li>

</ol>







<ol start="2">

 <li></li>

</ol>

(1) Given a knapsack of size 28, and the following 3 items:  Item 1, has profit 32 and size 8. Item 2, has profit 110 and size 20. Item 3, has profit 50 and size 5.   Solve the problem using the backtracking algorithm. Show the complete <strong>pruned</strong> state space tree. Show for every node, the current <strong>profit</strong>, the current <strong>weight</strong> and the <strong>bound</strong>. Show also the <strong>maxprofit</strong> after each node is generated. Show the order that the nodes to be checked.

(2) Using <strong>the best-first search</strong> algorithm (Branch-and-Bound) to solve the above problem. Show the order that the nodes to be checked.

<ol start="3">

 <li> Given an array A. Consider the following decision problem: is the 5000<sup>th</sup> largest element in the array greater than 100000?

  <ol>

   <li>Does this problem belong to the class P? Explain if no, or describe and analyze a polynomial bound algorithm that solves it.</li>

   <li>Does the problem belong to the class NP? Explain</li>

   <li>Does it belong to the class NPC (the class of NP-Complete problems)? (yes, no, probably) Explain [4%]</li>

  </ol></li>

</ol>







4.[10%] Professor Green showed a polynomial reduction of the famous decision problem CC to an NP-Complete problem. He also wrote an 80 page paper showing a polynomial bound algorithm for solving CC.

<ol>

 <li>Is CC in P? Is CC in NP? [5%]</li>

 <li>Should Professor Green get the $1,000,000 prize for showing that P = NP? Explain your answer. [5 %]</li>

 <li>[10%] Professor Watson showed a polynomial reduction of satisfiability to the famous decision problem YY. He also showed a polynomial bound verification algorithm for YY.

  <ol>

   <li>What does Professor Watson know about YY? [5%]</li>

   <li>Assume that the professor find a polynomial bound algorithm for YY. Should Professor Watson get the $1,000,000 prize for showing that P = NP? Explain your answer. [5 %]</li>

  </ol></li>

</ol>




<ol start="6">

 <li>[9%] A <em>clique</em> is a complete graph — every vertex is connected to every other vertex. Here is the formal definition from many textbooks: “<em>A </em><em>clique</em><em> in a graph is a set of pair-wise adjacent vertices, or in other words, an induced sub-graph which is a </em><em>complete graph</em><em>. In the following graph, vertices 1, 2 and 5 form a clique, because each has an edge to all the others</em>”.</li>

</ol>







Then, the decision-clique problem is the problem of determining whether a graph G contains a clique of at least a given size <em>k</em>. This problem is NP-complete.

Professor Bartlett has designed an algorithm that can take any graph <em>G</em> with <em>n</em> vertices and determine in  time whether or not <em>G</em> contains a clique of size <em>k</em>.  Has Professor Bartlett showed that <em>P</em> = <em>NP</em>?  Explain your answer.







<ol start="7">

 <li>[7%] Is the sum of subsets the decision problem or the optimization problem? Is it in NP? Explain why.</li>

</ol>




<ol start="8">

 <li>[7%] Show that 0-1 knapsack decision problem is NP-Complete (hint: sum of subsets is NP-Complete).</li>

</ol>







<ol start="9">

 <li>[12%] For each of the following problems, indicate which are in P and which are in NP. For those you think are in P, give an outline of the algorithm to solve them. For those you think are in NP, explain why you think they are not solvable in polynomial time. (Hint: think about an algorithm to solve these problems, and then determine if it is polynomial.)</li>

</ol>




<ol>

 <li>The Smarandache function, S(k), gives the smallest integer m, so that m! can be evenly divided by k. For example, S(9) = 6 because 6!=720 and 9 does not divide any smaller factorial. Calculate the Smarandache function for any number.</li>

 <li>You have to seat N children in the smallest number of rows in an auditorium. For each child, you have a list of who that child dislikes. Experience shows that if a child is in the same row or any row behind a child that he or she dislikes, he or she will throw things at the other child. Given this list, determine in which row to seat each child, or determine that they cannot be seated.</li>

 <li>You are in front of a wall that stretches infinitely in both directions. You know that there is a door in the wall, but it is dark, and you have only a dim flashlight that allows you to see no more than one step in either direction. Find the door.</li>

</ol>










<ol start="10">

 <li>(Optional: Extra point 12%) using the best-first search algorithm to give a solution of the following traveling salesman problem. Show the state space tree and the optimal tour [6%], and write a program to implement it [6%].</li>

</ol>








