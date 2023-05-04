Download Link: https://assignmentchef.com/product/solved-cs70-homework0
<br>
Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

Classify the following statements as being one of the following, where <em>x </em>and <em>y </em>are arbitrary propositions, and justify your answers (e.g., using a truth table)

<ul>

 <li>True for all combinations of <em>x </em>and <em>y </em>(Tautology)</li>

 <li>False for all combinations of <em>x </em>and <em>y </em>(Contradiction)</li>

 <li>Neither</li>

 <li><em>x</em>∧(<em>x </em>=⇒ <em>y</em>)∧(¬<em>y</em>)</li>

 <li><em>x </em>=⇒ (<em>x</em>∨<em>y</em>)</li>

 <li>(<em>x</em>∨<em>y</em>)∨(<em>x</em>∨¬<em>y</em>)</li>

 <li>(<em>x </em>=⇒ <em>y</em>)∨(<em>x </em>=⇒ ¬<em>y</em>)</li>

 <li>(<em>x</em>∨<em>y</em>)∧(¬(<em>x</em>∧<em>y</em>))</li>

 <li>(<em>x </em>=⇒ <em>y</em>)∧(¬<em>x </em>=⇒ <em>y</em>)∧(¬<em>y</em>)</li>

</ul>

<h1>2      Miscellaneous Logic</h1>

<ul>

 <li>Let the statement, (∀<em>x </em>∈ R)(∃<em>y </em>∈ R) <em>G</em>(<em>x</em><em>,</em><em>y</em>), be true for predicate <em>G</em>(<em>x</em><em>,</em><em>y</em>).</li>

</ul>

For each of the following statements, decide if the statement is certainly true, certainly false, or possibly true, and justify your solution. (If possibly true, provide a specific example where the statement is false and a specific example where the statement is true.)

<ul>

 <li><em>G</em>(3<em>,</em>4)</li>

 <li>(∀<em>x </em>∈ R) <em>G</em>(<em>x</em><em>,</em>3)</li>

 <li>∃<em>y G</em>(3<em>,</em><em>y</em>)</li>

 <li>∀<em>y </em>¬<em>G</em>(3<em>,</em><em>y</em>)</li>

 <li>∃<em>x G</em>(<em>x</em><em>,</em>4)</li>

</ul>

<ul>

 <li>Give an expression using terms involving ∨<em>,</em>∧ and ¬ which is true if and only if exactly one of <em>X</em><em>,</em><em>Y</em>, and <em>Z </em>is true.</li>

</ul>

<h1>3       Propositional Practice</h1>

Convert the following English sentences into propositional logic and the following propositions into English. State whether or not each statement is true with brief justification.

<ul>

 <li>There is a real number which is not rational.</li>

 <li>All integers are natural numbers or are negative, but not both.</li>

 <li>If a natural number is divisible by 6, it is divisible by 2 or it is divisible by 3.</li>

 <li>(∀<em>x </em>∈ R)(<em>x </em>∈ C)</li>

 <li>(∀<em>x </em>∈ Z)(((2 | <em>x</em>)∨(3 | <em>x</em>)) =⇒ (6 | <em>x</em>)) (f) (∀<em>x </em>∈ N)((<em>x </em><em>&gt; </em>7) =⇒ ((∃<em>a</em><em>,</em><em>b </em>∈ N)(<em>a</em>+<em>b </em>= <em>x</em>)))</li>

</ul>

4      Proof by?

<ul>

 <li>Prove that if for any two integers <em>x </em>and <em>y</em>, if 10 does not divide <em>xy</em>, then 10 does not divide <em>x </em>and 10 does not divide <em>y</em>. In notation: (∀<em>x</em><em>,</em><em>y </em>∈ Z) (10 – <em>xy</em>) =⇒ ((10 – <em>x</em>) ∧ (10 – <em>y</em>)). What proof technique did you use?</li>

 <li>Prove or disprove the contrapositive.</li>

 <li>Prove or disprove the converse.</li>

</ul>

<h1>5       Prove or Disprove</h1>

<ul>

 <li>(∀<em>n </em>∈ N) if <em>n </em>is odd then <em>n</em><sup>2 </sup>+2<em>n </em>is odd.</li>

 <li>(∀<em>x</em><em>,</em><em>y </em>∈ R) min(<em>x</em><em>,</em><em>y</em>)=(<em>x</em>+<em>y</em>−|<em>x</em>−<em>y</em>|)<em>/</em></li>

 <li>(∀<em>a</em><em>,</em><em>b </em>∈ R) if <em>a</em>+<em>b </em>≤ 10 then <em>a </em>≤ 7 or <em>b </em>≤</li>

 <li>(∀<em>r </em>∈ R) if <em>r </em>is irrational then <em>r</em>+1 is irrational.</li>

 <li>(∀<em>n </em>∈ Z<sup>+</sup>) 10<em>n</em><sup>2 </sup><em>&gt; </em><em>n</em>!.</li>

</ul>

<h1>6       Preserving Set Operations</h1>

For a function <em>f</em>, define the image of a set <em>X </em>to be the set <em>f</em>(<em>X</em>)= {<em>y </em>| <em>y </em>= <em>f</em>(<em>x</em>) for some <em>x </em>∈ <em>X</em>}. Define the inverse image or preimage of a set <em>Y </em>to be the set <em>f</em><sup>−</sup><sup>1</sup>(<em>Y</em>)= {<em>x </em>| <em>f</em>(<em>x</em>) ∈ <em>Y</em>}. Prove the following statements, in which <em>A </em>and <em>B </em>are sets. By doing so, you will show that inverse images preserve set operations, but images typically do not.

<em>Hint: For sets X and Y, X </em>=<em>Y if and only if X </em>⊆<em>Y and Y </em>⊆ <em>X. To prove that X </em>⊆<em>Y, it is sufficient to show that </em>(∀<em>x</em>)((<em>x </em>∈ <em>X</em>) =⇒ (<em>x </em>∈<em>Y</em>))<em>.</em>

(a) <em>f</em><sup>−</sup><sup>1</sup>(<em>A</em>∪<em>B</em>)= <em>f</em><sup>−</sup><sup>1</sup>(<em>A</em>)∪ <em>f</em><sup>−</sup><sup>1</sup>(<em>B</em>). (b) <em>f</em><sup>−</sup><sup>1</sup>(<em>A</em>∩<em>B</em>)= <em>f</em><sup>−</sup><sup>1</sup>(<em>A</em>)∩ <em>f</em><sup>−</sup><sup>1</sup>(<em>B</em>).

<ul>

 <li><em>f</em><sup>−</sup><sup>1</sup>(<em>A</em><em>B</em>)= <em>f</em><sup>−</sup><sup>1</sup>(<em>A</em>) <em>f</em><sup>−</sup><sup>1</sup>(<em>B</em>).</li>

 <li><em>f</em>(<em>A</em>∪<em>B</em>)= <em>f</em>(<em>A</em>)∪ <em>f</em>(<em>B</em>).</li>

 <li><em>f</em>(<em>A</em>∩<em>B</em>) ⊆ <em>f</em>(<em>A</em>)∩ <em>f</em>(<em>B</em>), and give an example where equality does not hold.</li>

 <li><em>f</em>(<em>A</em><em>B</em>) ⊇ <em>f</em>(<em>A</em>) <em>f</em>(<em>B</em>), and give an example where equality does not hold.</li>

</ul>




<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

State which of the proofs below is correct or incorrect. For the incorrect ones, please explain clearly where the logical error in the proof lies. Simply saying that the claim or the induction hypothesis is false is <em>not </em>a valid explanation of what is wrong with the proof. You do not need to elaborate if you think the proof is correct.

<ul>

 <li>Claim: For all positive numbers <em>n </em>∈ R, <em>n</em><sup>2 </sup>≥ <em>n</em>.</li>

</ul>

<em>Proof. </em>The proof will be by induction on <em>n</em>.

<em>Base Case: </em>1<sup>2 </sup>≥ 1. It is true for <em>n </em>= 1.

<em>Inductive Hypothesis: </em>Assume that <em>n</em><sup>2 </sup>≥ <em>n</em>.

<em>Inductive Step: </em>We must prove that (<em>n</em>+1)<sup>2 </sup>≥ <em>n</em>+1. Starting from the left hand side,

(<em>n</em>+1)<sup>2 </sup>= <em>n</em><sup>2 </sup>+2<em>n</em>+1 ≥ <em>n</em>+1<em>.</em>

Therefore, the statement is true.

<ul>

 <li>Claim: For all negative integers <em>n</em>, (−1)+(−3)+···+(2<em>n</em>+1)= −<em>n</em><sup>2</sup>.</li>

</ul>

<em>Proof. </em>The proof will be by induction on <em>n</em>.

<em>Base Case: </em>−1 = −(−1)<sup>2</sup>. It is true for <em>n </em>= −1.

<em>Inductive Hypothesis: </em>Assume that (−1)+(−3)+···+(2<em>n</em>+1)= −<em>n</em><sup>2</sup>.

<em>Inductive Step: </em>We need to prove that the statement is also true for <em>n</em>−1 if it is true for <em>n</em>, that is, (−1)+(−3)+···+(2(<em>n</em>−1)+1)= −(<em>n</em>−1)<sup>2</sup>. Starting from the left hand side,

(−1)+(−3)+···+(2(<em>n</em>−1)+1)=((−1)+(−3)+···+(2<em>n</em>+1))+(2(<em>n</em>−1)+1)

= −<em>n</em><sup>2 </sup>+(2(<em>n</em>−1)+1) (Inductive Hypothesis)

= −<em>n</em><sup>2 </sup>+2<em>n</em>−1

= −(<em>n</em><sup>2 </sup>−2<em>n</em>+1) = −(<em>n</em>−1)<sup>2</sup><em>.</em>

Therefore, the statement is true.

(c) Claim: For all nonnegative integers <em>n</em>, 2<em>n </em>= 0.

<em>Proof. </em>We will prove by strong induction on <em>n</em>.

<em>Base Case: </em>2×0 = 0. It is true for <em>n </em>= 0.

<em>Inductive Hypothesis: </em>Assume that 2<em>k </em>= 0 for all 0 ≤ <em>k </em>≤ <em>n</em>.

<em>Inductive Step: </em>We must show that 2(<em>n</em>+1)= 0. Write <em>n</em>+1 = <em>a</em>+<em>b </em>where 0 <em>&lt; </em><em>a</em><em>,</em><em>b </em>≤ <em>n</em>. From the inductive hypothesis, we know 2<em>a </em>= 0 and 2<em>b </em>= 0, therefore,

2(<em>n</em>+1)= 2(<em>a</em>+<em>b</em>)= 2<em>a</em>+2<em>b </em>= 0+0 = 0<em>.</em>

The statement is true.

<h1>2       A Coin Game</h1>

Your “friend” Stanley Ford suggests you play the following game with him. You each start with a single stack of <em>n </em>coins. On each of your turns, you select one of your stacks of coins (that has at least two coins) and split it into two stacks, each with at least one coin. Your score for that turn is the product of the sizes of the two resulting stacks (for example, if you split a stack of 5 coins into a stack of 3 coins and a stack of 2 coins, your score would be 3·2 = 6). You continue taking turns until all your stacks have only one coin in them. Stan then plays the same game with his stack of <em>n </em>coins, and whoever ends up with the largest total score over all their turns wins.

Prove that no matter how you choose to split the stacks, your total score will always be <em><sup>n</sup></em>.

(This means that you and Stan will end up with the same score no matter what happens, so the game is rather pointless.)

<h1>3       Grid Induction</h1>

Pacman is walking on an infinite 2D grid. He starts at some location (<em>i</em><em>, </em><em>j</em>)∈N<sup>2 </sup>in the first quadrant, and is constrained to stay in the first quadrant (say, by walls along the x and y axes). Every second he does one of the following (if possible):

<ul>

 <li>Walk one step down, to (<em>i</em><em>, </em><em>j</em>−1).</li>

 <li>Walk one step left, to (<em>i</em>−1<em>, </em><em>j</em>).</li>

</ul>

For example, if he is at (5<em>,</em>0), his only option is to walk left to (4<em>,</em>0); if Pacman is instead at (3<em>,</em>2), he could walk either to (2<em>,</em>2) or (3<em>,</em>1).

Prove by induction that no matter how he walks, he will always reach (0<em>,</em>0) in finite time. (<em>Hint</em>: Try starting Pacman at a few small points like (2<em>,</em>1) and looking all the different paths he could take to reach (0<em>,</em>0). Do you notice a pattern?)

<h1>4      Stable Marriage</h1>

Consider a set of four men and four women with the following preferences:

<table width="298">

 <tbody>

  <tr>

   <td width="44">men</td>

   <td width="92">preferences</td>

   <td width="65">women</td>

   <td width="98">preferences</td>

  </tr>

  <tr>

   <td width="44">A</td>

   <td width="92">1<em>&gt;</em>2<em>&gt;</em>3<em>&gt;</em>4</td>

   <td width="65">1</td>

   <td width="98">D<em>&gt;</em>A<em>&gt;</em>B<em>&gt;</em>C</td>

  </tr>

  <tr>

   <td width="44"> </td>

   <td width="92">1<em>&gt;</em>3<em>&gt;</em>2<em>&gt;</em>4</td>

   <td width="65">2</td>

   <td width="98"><em>&gt;</em>B<em>&gt;</em>C<em>&gt;</em></td>

  </tr>

  <tr>

   <td width="44"> </td>

   <td width="92">1<em>&gt;</em>3<em>&gt;</em>2<em>&gt;</em>4</td>

   <td width="65">3</td>

   <td width="98"><em>&gt;</em>B<em>&gt;</em>C<em>&gt;</em></td>

  </tr>

  <tr>

   <td width="44">D</td>

   <td width="92">3<em>&gt;</em>1<em>&gt;</em>2<em>&gt;</em>4</td>

   <td width="65">4</td>

   <td width="98">A<em>&gt;</em>B<em>&gt;</em>D<em>&gt;</em>C</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Run on this instance the stable matching algorithm presented in class. Show each day of the algorithm, and give the resulting matching, expressed as {(<em>M</em><em>,</em><em>W</em>)<em>,…</em>}.</li>

 <li>Suppose we relax the rules for the men, so that each unpaired man proposes to the next woman on his list at a time of his choice (some men might procrastinate for several days, while others might propose and get rejected several times in a single day). Prove that this modification will not change what pairing the algorithm outputs.</li>

</ul>

<h1>5       Optimal Partners</h1>

In the notes, we proved that the Stable Marriage Algorithm always outputs the male-optimal pairing. However, we never explicitly showed why it is guaranteed that putting every man with his best choice results in a pairing at all. Prove by contradiction that no two men can have the same optimal partner. (Note: your proof should not rely on the fact that the Stable Marriage Algorithm outputs the male-optimal pairing.)

<h1>6        Examples or It’s Impossible</h1>

Determine if each of the situations below is possible with the traditional propose-and-reject algorithm. If so, give an example with at least 3 men and 3 women. Otherwise, give a brief proof as to why it’s impossible.

<ul>

 <li>Every man gets his first choice.</li>

 <li>Every woman gets her first choice, even though her first choice does not prefer her the most. (c) Every woman gets her last choice.</li>

 <li>Every man gets his last choice.</li>

 <li>A man who is second on every woman’s list gets his last choice.</li>

</ul>




CS 70                          Discrete Mathematics and Probability Theory

<h1>Fall 2018                  Alistair Sinclair and Yun Song                                                  HW3</h1>

Due: September 7, 2018 at 10 PM

<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with?

List names and email addresses. (In case of homework party, you can just describe the group.)

<h1>1       Short Answer: Graphs</h1>

<ul>

 <li>Bob removed a degree 3 node in an <em>n</em>-vertex tree, how many connected components are in the resulting graph? (An expression that may contain <em>n</em>.)</li>

 <li>Given an <em>n</em>-vertex tree, Bob added 10 edges to it, then Alice removed 5 edges and the resulting graph has 3 connected components. How many edges must be removed to remove all cycles in the resulting graph? (An expression that may contain <em>n</em>.)</li>

 <li>True or False: For all <em>n </em>3, the complete graph on <em>n </em>vertices, <em>K<sub>n </sub></em>has more edges than the <em>n</em>-dimensional hypercube. Justify your answer.</li>

 <li>A complete graph with <em>n </em>vertices where <em>n </em>is an odd prime can have all its edges covered with <em>x </em>Hamiltonian cycles (a Hamiltonian cycle is a cycle where each vertex appears exactly once). What is the number, <em>x</em>, of such cycles required to cover the a complete graph? (Answer should be an expression that depends on <em>n</em>.)</li>

 <li>Give a set of edge-disjoint Hamiltonian cycles that covers the edges of <em>K</em><sub>5</sub>, the complete graph on 5 vertices. (Each path should be a sequence (or list) of edges in <em>K</em><sub>5</sub>, where an edge is written as a pair of vertices from the set {0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>4} – e.g: (0<em>,</em>1)<em>,</em>(1<em>,</em>2).)</li>

</ul>

<h1>2         Eulerian Tour and Eulerian Walk</h1>

<ul>

 <li>Is there an Eulerian tour in the graph above?</li>

 <li>Is there an Eulerian walk in the graph above?</li>

 <li>What is the condition that there is an Eulerian walk in an undirected graph? Briefly justfy your answer.</li>

</ul>

<h1>3       Bipartite Graph</h1>

A bipartite graph consists of 2 disjoint sets of vertices (say <em>L </em>and <em>R</em>), such that no 2 vertices in the same set have an edge between them. For example, here is a bipartite graph (with <em>L </em>= {green vertices} and <em>R </em>={red vertices}), and a non-bipartite graph.

Figure 1: A bipartite graph (left) and a non-bipartite graph (right).

Prove that a graph is bipartite if and only if it has no tours of odd length.

<h1>4      Hypercubes</h1>

The vertex set of the{and only if <em>n</em>-dimensional hypercube <em>G </em>= (<em>V</em><em>,</em><em>E</em>) is given by <em>V </em>= {0<em>,</em>1}<em><sup>n </sup></em>(<em>x</em>recall thatand <em>y </em>if

0<em>,</em>1}<em><sup>n </sup></em>denotes the set of all<em>x </em>and <em>y </em>differ in exactly one bit position. These problems will help you understand<em>n</em>-bit strings). There is an edge between two vertices hypercubes.

<ul>

 <li>Draw 1-, 2-, and 3-dimensional hypercubes and label the vertices using the corresponding bit strings.</li>

 <li>Show that for any <em>n </em>1, the <em>n</em>-dimensional hypercube is <em>bipartite</em>: the vertices can be partitioned into two groups so that every edge goes between the two groups.</li>

</ul>

<h1>5        Triangulated Planar Graph</h1>

In this problem you will prove that every triangulated planar graph (every face has 3 sides; that is, every face has three edges bordering it, including the unbounded face) contains either (1) a vertex of degree 1, 2, 3, 4, (2) two degree 5 vertices which are adjacent, or (3) a degree 5 and a degree 6 vertices which are adjacent. Justify your answers.

(a) Place a “charge” on each vertex <em>v </em>of value 6 degree(<em>v</em>). What is the sum of the charges on all the vertices? (<em>Hint</em>: Use Euler’s formula and the fact that the planar graph is triangulated.) (b) What is the charge of a degree 5 vertex and of a degree 6 vertex?

<ul>

 <li>Suppose now that we shift 1<em>/</em>5 of the charge of a degree 5 vertex to each of its neighbors that has a negative charge. (We refer to this as “discharging” the degree 5 vertex.) Conclude the proof under the assumption that, after discharging all degree 5 vertices, there is a degree 5 vertex with positive remaining charge.</li>

 <li>If no degree 5 vertices have positive charge after discharging the degree 5 vertices, does there exist any vertex with positive charge after discharging? If there is such a vertex, what are the possible degrees of that vertex?</li>

 <li>Suppose there exists a degree 7 vertex with positive charge after discharging the degree 5 vertices. How many neighbors of degree 5 might it have?</li>

 <li>Continuing from Part (e). Since the graph is triangulated, are two of these degree 5 vertices adjacent?</li>

 <li>Finish the proof from the facts you obtained from the previous parts.</li>

</ul>




CS 70                          Discrete Mathematics and Probability Theory

Fall 2018                  Alistair Sinclair and Yun Song                                                  HW4

Due: September 21, 2018 at 10 PM

Sundry

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

Find all solutions (modulo the corresponding modulus) to the following equations. Prove that there are no other solutions (in a modular setting) to each equation.

<ul>

 <li>2<em>x </em>≡ 5 (mod 15)</li>

 <li>2<em>x </em>≡ 5 (mod 16) (c) 5<em>x </em>≡ 10 (mod 25)</li>

</ul>

2       Euclid’s Algorithm

<ul>

 <li>Use Euclid’s algorithm from lecture to compute the greatest common divisor of 527 and 323. List the values of <em>x </em>and <em>y </em>of all recursive calls.</li>

 <li>Use extended Euclid’s algorithm from lecture to compute the multiplicative inverse of 5 mod</li>

</ul>

<ol start="27">

 <li>List the values of <em>x </em>and <em>y </em>and the returned values of all recursive calls.</li>

</ol>

<ul>

 <li>Find <em>x </em>(mod 27) if 5<em>x</em>+26 ≡ 3 (mod 27). You can use the result computed in (b).</li>

 <li>Assume <em>a</em>, <em>b</em>, and <em>c </em>are integers and <em>c </em><em>&gt; </em> Prove or disprove: If <em>a </em>has no multiplicative inverse mod <em>c</em>, then <em>ax </em>≡ <em>b </em>(mod <em>c</em>) has no solution.</li>

</ul>

3        Modular Exponentiation

Compute the following:

<ul>

 <li>13<sup>2018 </sup>(mod 12)</li>

 <li>8<sup>11111 </sup>(mod 9)</li>

 <li>7<sup>256 </sup>(mod 11)</li>

 <li>3<sup>160 </sup>(mod 23)</li>

</ul>

4        Euler’s Totient Function

Euler’s totient function is defined as follows:

<em>φ</em>(<em>n</em>)= |{<em>i </em>: 1 ≤ <em>i </em>≤ <em>n</em><em>,</em>gcd(<em>n</em><em>,</em><em>i</em>)= 1}|

In other words, <em>φ</em>(<em>n</em>) is the total number of positive integers less than or equal to <em>n </em>which are relatively prime to it. Here is a property of Euler’s totient function that you can use without proof:

For <em>m</em><em>,</em><em>n </em>such that gcd(<em>m</em><em>,</em><em>n</em>) = 1, <em>φ</em>(<em>mn</em>)=<em>φ</em>(<em>m</em>)·<em>φ</em>(<em>n</em>).

<ul>

 <li>Let <em>p </em>be a prime number. What is <em>φ</em>(<em>p</em>)?</li>

 <li>Let <em>p </em>be a prime number and <em>k </em>be some positive integer. What is <em>φ</em>(<em>p<sup>k</sup></em>)?</li>

 <li>Let <em>p </em>be a prime number and <em>a </em>be a positive integer smaller than <em>p</em>. What is <em>a<sup>φ</sup></em><sup>(</sup><em><sup>p</sup></em><sup>) </sup>(mod <em>p</em>)? <em>(Hint: use Fermat’s Little Theorem.)</em></li>

 <li>Let <em>b </em>be a positive integer whose prime factors are <em>p</em><sub>1</sub><em>, </em><em>p</em><sub>2</sub><em>,…, </em><em>p<sub>k</sub></em>. We can write <em>b </em><em>p</em><em> … </em><em>p<sup>α</sup><sub>k</sub></em><em><sup>k</sup></em>.</li>

</ul>

Show that for any <em>a </em>relatively prime to <em>b</em>, the following holds:

∀<em>i </em>∈ {1<em>,</em>2<em>,…,</em><em>k</em>}<em>, </em><em>a<sup>φ</sup></em><sup>(</sup><em><sup>b</sup></em><sup>) </sup>≡ 1 (mod <em>p<sub>i</sub></em>)

5       FLT Converse

Recall that the FLT states that, given a prime <em>n</em>, <em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡ 1 (mod <em>n</em>) <em>for all </em>1 ≤ <em>a </em>≤ <em>n</em>−1. Note that it says nothing about when <em>n </em>is composite.

Can the FLT condition (<em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡ 1 mod <em>n</em>) hold for some or even all <em>a </em>if <em>n </em>is composite? This problem will investigate both possibilities. It turns out that unlike in the prime case, we need to restrict ourselves to looking at <em>a </em>that are relatively prime to <em>n</em>. (Note that if <em>n </em>is prime, then every <em>a </em><em>&lt; </em><em>n </em>is relatively prime to <em>n</em>). Because of this restriction, let’s define

<em>S</em>(<em>n</em>)= {<em>i </em>: 1 ≤ <em>i </em>≤ <em>n</em><em>,</em>gcd(<em>n</em><em>,</em><em>i</em>)= 1}<em>,</em>

so | <em>S </em>| is the total number of possible choices for <em>a</em>.

<ul>

 <li>Prove that for every <em>a </em>and <em>n </em>that are not relatively prime, FLT condition fails. In other words, for every <em>a </em>and <em>n </em>such that gcd(<em>n</em><em>,</em><em>a</em>) 6= 1, we have <em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡6 1 (mod <em>n</em>).</li>

 <li>Prove that the FLT condition fails for most choices of <em>a </em>and <em>n</em>. More precisely, show that if we can find a single <em>a </em>∈ <em>S</em>(<em>n</em>) such that <em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡6 1 (mod <em>n</em>), we can find at least |<em>S</em>(<em>n</em>)|<em>/</em>2 such <em>a</em>. (Hint: You’re almost there if you can show that the set of numbers that fail the FLT condition is at least as large as the set of numbers that pass it. A clever bijection may be useful to compare set sizes.)</li>

</ul>

The above tells us that if a composite number fails the FLT condition for even one number relatively prime to it, then it fails the condition for most numbers relatively prime to it. However, it doesn’t rule out the possibility that some composite number <em>n </em>satisifes the FLT condition entirely: <em>for all a </em>relatively prime to <em>n</em>, <em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡ 1 mod <em>n</em>. It turns out such numbers do exist, but they were found through trial-and-error! We will prove one of the conditions on <em>n </em>that make it easy to verify the existence of these numbers.

<ul>

 <li>First, show that if <em>a </em>≡ <em>b </em>mod <em>m</em><sub>1 </sub>and <em>a </em>≡ <em>b </em>mod <em>m</em><sub>2</sub>, with gcd(<em>m</em><sub>1</sub><em>,</em><em>m</em><sub>2</sub>) = 1, then <em>a </em>≡ <em>b </em>(mod <em>m</em><sub>1</sub><em>m</em><sub>2</sub>).</li>

 <li>Let <em>n </em>= <em>p</em><sub>1</sub><em>p</em><sub>2 </sub>·· <em>p<sub>k </sub></em>where <em>p<sub>i </sub></em>are distinct primes and <em>p<sub>i </sub></em>−1 | <em>n</em>−1 for all <em>i</em>. Show that <em>a<sup>n</sup></em><sup>−</sup><sup>1 </sup>≡ 1 (mod <em>n</em>) for all <em>a </em>∈ <em>S</em>(<em>n</em>)</li>

 <li>Verify that for all <em>a </em>coprime with 561, <em>a</em><sup>560 </sup>≡ 1 (mod 561).</li>

</ul>




CS 70                          Discrete Mathematics and Probability Theory

Fall 2018                  Alistair Sinclair and Yun Song                                                  HW5

Due: Friday, 9/28, 10pm Sundry

Before you start your homework, state briefly how you worked on it. Who else did you work with?

List names and email addresses. (In case of homework party, you can just describe the group.)

Simplify each expression using Fermat’s Little Theorem.

<ul>

 <li>3<sup>33 </sup>(mod 11)</li>

 <li>10001<sup>10001 </sup>(mod 17)</li>

 <li>10<sup>10 </sup>+20<sup>20 </sup>+30<sup>30 </sup>+40<sup>40 </sup>(mod 7)</li>

</ul>

2       RSA Practice

Bob would like to receive encrypted messages from Alice via RSA.

<ul>

 <li>Bob chooses <em>p</em>= 7 and <em>q</em>= His public key is (<em>N</em><em>,</em><em>e</em>). What is <em>N</em>?</li>

 <li>What number is <em>e </em>relatively prime to?</li>

 <li><em>e </em>need not be prime itself, but what is the smallest prime number <em>e </em>can be? Use this value for <em>e </em>in all subsequent computations.</li>

 <li>What is gcd(<em>e</em><em>,</em>(<em>p</em>−1)(<em>q</em>−1))?</li>

 <li>What is the decryption exponent <em>d</em>?</li>

 <li>Now imagine that Alice wants to send Bob the message 30. She applies her encryption function <em>E </em>to 30. What is her encrypted message?</li>

</ul>

CS 70, Fall 2018, HW 5                                                                                                                                                                          1

<ul>

 <li>Bob receives the encrypted message, and applies his decryption function <em>D </em>to it. What is <em>D </em>applied to the received message?</li>

</ul>

3       Squared RSA

<ul>

 <li>Prove the identity <em>a<sup>p</sup></em><sup>(</sup><em><sup>p</sup></em><sup>−</sup><sup>1</sup><sup>) </sup>≡ 1 (mod <em>p</em><sup>2</sup>), where <em>a </em>is coprime to <em>p</em>, and <em>p </em>is prime. (Hint: Try to mimic the proof of Fermat’s Little Theorem from the notes.)</li>

 <li>Now consider the RSA scheme: the public key is (<em>N </em>= <em>p</em><sup>2</sup><em>q</em><sup>2</sup><em>,</em><em>e</em>) for primes <em>p </em>and <em>q</em>, with <em>e </em>relatively prime to <em>p</em>(<em>p</em>− 1)<em>q</em>(<em>q</em>− 1). The private key is <em>d </em>= <em>e</em><sup>−</sup><sup>1 </sup>(mod <em>p</em>(<em>p</em>− 1)<em>q</em>(<em>q</em>− 1)). Prove that the scheme is correct for <em>x </em>relatively prime to both <em>p </em>and <em>q</em>, i.e. <em>x<sup>ed </sup></em>≡<em>x </em>(mod <em>N</em>).</li>

 <li>Prove that this scheme is at least as hard to break as normal RSA; that is, prove that if this scheme can be broken, normal RSA can be as well. We consider RSA to be broken if knowing <em>pq </em>allows you to deduce (<em>p</em>−1)(<em>q</em>−1). We consider squared RSA to be broken if knowing <em>p</em><sup>2</sup><em>q</em><sup>2 </sup>allows you to deduce <em>p</em>(<em>p</em>−1)<em>q</em>(<em>q</em>−1).</li>

</ul>




<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

<ul>

 <li>If <em>f </em>and <em>g </em>are non-zero real polynomials, how many roots do the following polynomials have at least? How many can they have at most? (Your answer may depend on the degrees of <em>f </em>and <em>g</em>.)

  <ul>

   <li><em>f </em>+<em>g</em></li>

   <li><em>f </em><em>g</em></li>

   <li><em>f</em><em>/</em><em>g</em>, assuming that <em>f</em><em>/</em><em>g </em>is a polynomial</li>

  </ul></li>

 <li>Now let <em>f </em>and <em>g </em>be polynomials over GF(<em>p</em>).

  <ul>

   <li>If <em>f </em><em>g </em>= 0, is it true that either <em>f </em>= 0 or <em>g </em>= 0?</li>

   <li>If deg <em>f </em>≥ <em>p</em>, show that there exists a polynomial <em>h </em>with deg<em>h </em><em>&lt; </em><em>p </em>such that <em>f</em>(<em>x</em>)= <em>h</em>(<em>x</em>) for all <em>x </em>∈ {0<em>,</em>1<em>,…,</em><em>p</em>−1}.</li>

   <li>How many <em>f </em>of degree <em>exactly d </em><em>&lt; </em><em>p </em>are there such that <em>f</em>(0)= <em>a </em>for some fixed <em>a </em>∈ {0<em>,</em>1<em>,…,</em><em>p</em>−1}?</li>

  </ul></li>

 <li>Find a polynomial <em>f </em>over GF(5) that satisfies <em>f</em>(0)= 1<em>, </em><em>f</em>(2)= 2<em>, </em><em>f</em>(4)= How many such polynomials are there?</li>

</ul>

<h1>2          The CRT and Lagrange Interpolation</h1>

Let <em>n</em><sub>1</sub><em>,…</em><em>n<sub>k </sub></em>be pairwise coprime, i.e. <em>n<sub>i </sub></em>and <em>n<sub>j </sub></em>are coprime for all <em>i </em>6= <em>j</em>. The Chinese Remainder Theorem (CRT) tells us that there exist solutions to the following system of congruences:

<table width="371">

 <tbody>

  <tr>

   <td width="352"><em>x </em>≡ <em>a</em><sub>1 </sub>(mod <em>n</em><sub>1</sub>)</td>

   <td width="19">(1)</td>

  </tr>

  <tr>

   <td width="352"><em>x </em>≡ <em>a</em><sub>2 </sub>(mod <em>n</em><sub>2</sub>)</td>

   <td width="19">(2)</td>

  </tr>

  <tr>

   <td width="352">…</td>

   <td width="19">.(<sup>.</sup>.)</td>

  </tr>

  <tr>

   <td width="352"><em>x </em>≡ <em>a<sub>k </sub></em>(mod <em>n<sub>k</sub></em>)</td>

   <td width="19">(<em>k</em>)</td>

  </tr>

 </tbody>

</table>

and all solutions are equivalent (mod <em>n</em><sub>1</sub><em>n</em><sub>2 </sub>···<em>n<sub>k</sub></em>). For this problem, parts (a)-(c) will walk us through a proof of the Chinese Remainder Theorem. We will then use the CRT to revisit Lagrange interpolation.

<ul>

 <li>We start by proving the <em>k </em>= 2 case: Prove that we can always find an integer <em>x</em><sub>1 </sub>that solves (1) and (2) with <em>a</em><sub>1 </sub>= 1<em>,</em><em>a</em><sub>2 </sub>= Similarly, prove that we can always find an integer <em>x</em><sub>2 </sub>that solves (1) and (2) with <em>a</em><sub>1 </sub>= 0<em>,</em><em>a</em><sub>2 </sub>= 1.</li>

 <li>Use part (a) to prove that we can always find at least one solution to (1) and (2) for any <em>a</em><sub>1</sub><em>,</em><em>a</em><sub>2</sub>. Furthermore, prove that all possible solutions are equivalent (mod <em>n</em><sub>1</sub><em>n</em><sub>2</sub>).</li>

 <li>Now we can tackle the case of arbitrary <em>k</em>: Use part (b) to prove that there exists a solution <em>x </em>to (1)-(<em>k</em>) and that this solution is unique (mod <em>n</em><sub>1</sub><em>n</em><sub>2 </sub>··<em>n<sub>k</sub></em>).</li>

 <li>For two polynomials <em>p</em>(<em>x</em>) and <em>q</em>(<em>x</em>), mimic the definition of <em>a </em>mod <em>b </em>for integers to define <em>p</em>(<em>x</em>) mod <em>q</em>(<em>x</em>). Use your definition to find <em>p</em>(<em>x</em>) mod (<em>x</em>−1).</li>

 <li>Define the polynomials <em>x</em>−<em>a </em>and <em>x</em>−<em>b </em>to be coprime if they have no common divisor of degree 1. Assuming that the CRT still holds when replacing <em>x</em><em>,</em><em>a<sub>i </sub></em>and <em>n<sub>i </sub></em>with polynomials (using the definition of coprime polynomials just given), show that the system of congruences</li>

</ul>

<em>p</em>(<em>x</em>) ≡ <em>y</em><sub>1 </sub>(mod (<em>x</em>−<em>x</em><sub>1</sub>))   (1’) <em>p</em>(<em>x</em>) ≡ <em>y</em><sub>2 </sub>(mod (<em>x</em>−<em>x</em><sub>2</sub>))     (2’)

…                                                                                   (…)

<em>p</em>(<em>x</em>) ≡ <em>y<sub>k </sub></em>(mod (<em>x</em>−<em>x<sub>k</sub></em>))                                                   (k’)

has a unique solution (mod (<em>x</em>−<em>x</em><sub>1</sub>)···(<em>x</em>−<em>x<sub>k</sub></em>)) whenever the <em>x<sub>i </sub></em>are pairwise distinct. What is the connection to Lagrange interpolation?

<h1>3      Old secrets, new secrets</h1>

In order to share a secret number <em>s</em>, Alice distributed the values (1<em>,</em><em>p</em>(1))<em>,</em>(2<em>,</em><em>p</em>(2))<em>,…,</em>(<em>n</em>+1<em>,</em><em>p</em>(<em>n</em>+1)) of a degree <em>n </em>polynomial <em>p </em>with her friends Bob<sub>1</sub><em>,…,</em>Bob<em><sub>n</sub></em><sub>+</sub><sub>1</sub>. As usual, she chose <em>p </em>such that <em>p</em>(0)= <em>s</em>. Bob<sub>1 </sub>through Bob<em><sub>n</sub></em><sub>+</sub><sub>1 </sub>now gather to jointly discover the secret. Suppose that for some reason Bob<sub>1 </sub>already knows <em>s</em>, and wants to play a joke on Bob<sub>2</sub><em>,…,</em>Bob<em><sub>n</sub></em><sub>+</sub><sub>1</sub>, making them believe that the secret is in fact some fixed <em>s</em><sup>0 </sup>6= <em>s</em>. How can he achieve this?

<h1>4        Berlekamp-Welch for General Errors</h1>

Suppose that Hector wants to send you a length <em>n </em>= 3 message, <em>m</em><sub>0</sub><em>,</em><em>m</em><sub>1</sub><em>,</em><em>m</em><sub>2</sub>, with the possibility for <em>k </em>= 1 error. For all parts of this problem, we will work mod 11, so we can encode 11 letters as shown below:

<table width="294">

 <tbody>

  <tr>

   <td width="36">A</td>

   <td width="27">B</td>

   <td width="27">C</td>

   <td width="27">D</td>

   <td width="26">E</td>

   <td width="25">F</td>

   <td width="27">G</td>

   <td width="27">H</td>

   <td width="24">I</td>

   <td width="24">J</td>

   <td width="24">K</td>

  </tr>

  <tr>

   <td width="36">0</td>

   <td width="27">1</td>

   <td width="27">2</td>

   <td width="27">3</td>

   <td width="26">4</td>

   <td width="25">5</td>

   <td width="27">6</td>

   <td width="27">7</td>

   <td width="24">8</td>

   <td width="24">9</td>

   <td width="24">10</td>

  </tr>

 </tbody>

</table>

Hector encodes the message by finding the degree ≤ 2 polynomial <em>P</em>(<em>x</em>) that passes through (0<em>,</em><em>m</em><sub>0</sub>), (1<em>,</em><em>m</em><sub>1</sub>), and (2<em>,</em><em>m</em><sub>2</sub>), and then sends you the five packets <em>P</em>(0)<em>,</em><em>P</em>(1)<em>,</em><em>P</em>(2)<em>,</em><em>P</em>(3)<em>,</em><em>P</em>(4) over a noisy channel. The message you receive is

DHACK ⇒ 3<em>,</em>7<em>,</em>0<em>,</em>2<em>,</em>10 = <em>r</em><sub>0</sub><em>,</em><em>r</em><sub>1</sub><em>,</em><em>r</em><sub>2</sub><em>,</em><em>r</em><sub>3</sub><em>,</em><em>r</em><sub>4</sub>

which could have up to 1 error.

<ul>

 <li>First, let’s locate the error, using an error-locating polynomial <em>E</em>(<em>x</em>). Let <em>Q</em>(<em>x</em>) = <em>P</em>(<em>x</em>)<em>E</em>(<em>x</em>).</li>

</ul>

Recall that

<em>Q</em>(<em>i</em>)= <em>P</em>(<em>i</em>)<em>E</em>(<em>i</em>)= <em>r<sub>i</sub>E</em>(<em>i</em>)<em>,        </em>for      0 ≤ <em>i </em><em>&lt; </em><em>n</em>+2<em>k</em><em>.</em>

What is the degree of <em>E</em>(<em>x</em>)? What is the degree of <em>Q</em>(<em>x</em>)? Using the relation above, write out the form of <em>E</em>(<em>x</em>) and <em>Q</em>(<em>x</em>) in terms of the unknown coefficients, and then a system of equations to find both these polynomials.

<ul>

 <li>Solve for <em>Q</em>(<em>x</em>) and <em>E</em>(<em>x</em>). Where is the error located?</li>

 <li>Finally, what is <em>P</em>(<em>x</em>)? Use <em>P</em>(<em>x</em>) to determine the original message that Hector wanted to send.</li>

</ul>

<h1>5       Error-Detecting Codes</h1>

Suppose Alice wants to transmit a message of <em>n </em>symbols, so that Bob is able to <em>detect </em>rather than <em>correct </em>any errors that have occured on the way. That is, Alice wants to find an encoding so that

Bob, upon receiving the code, is able to either

<ul>

 <li>tell that there are no errors and decode the message, or</li>

 <li>realize that the transmitted code contains at least one error, and throw away the message.</li>

</ul>

Assuming that we are guaranteed a maximum of <em>k </em>errors, how should Alice extend her message (i.e. by how many symbols should she extend the message, and how should she choose these symbols)? You may assume that we work in GF(<em>p</em>) for very large prime <em>p</em>. Show that your scheme works, and that adding any lesser number of symbols is not good enough.




CS 70                          Discrete Mathematics and Probability Theory

Fall 2018                  Alistair Sinclair and Yun Song                            Homework 7

Due: Friday, August 3, 2018 at 10 PM

Sundry

Before you start your homework, state briefly how you worked on it. Who else did you work with?

List names and email addresses. (In case of homework party, you can just describe the group.)

1       Bijective or not?

Decide whether the following functions are bijections or not. Please prove your claims.

<ul>

 <li><em>f</em>(<em>x</em>)= 10 <sup>5</sup><em>x</em>

  <ul>

   <li>for domain R and range R</li>

   <li>for domain Z[{<em>p</em>} and range R</li>

  </ul></li>

 <li><em>f</em>(<em>x</em>)= <em>p </em>mod <em>x</em>, where <em>p </em><em>&gt; </em>2 is a prime

  <ul>

   <li>for domain N{0} and range {0<em>,…,</em><em>p</em>}</li>

   <li>for domain {(<em>p</em>+1)<em>/</em>2<em>,…,</em><em>p</em>} and range {0<em>,…,</em>(<em>p </em>1)<em>/</em>2}</li>

  </ul></li>

 <li><em>f</em>(<em>x</em>)={<em>x</em>}, where the domain is<em>D</em>).<em>D </em>={0<em>,…,</em><em>n</em>} and the range is <em>P</em>(<em>D</em>), the powerset of <em>D </em>(that is, the set of all subsets of</li>

 <li>Consider the number <em>X </em>= 1234567890, and obtain <em>X</em>0 by shuffling the order of the digits of <em>X</em>. Is <em>f</em>(<em>i</em>)=(i+1)<sup>st </sup><em>digit of X</em>0 a bijection from {0<em>,…,</em>9} to itself?</li>

</ul>

2       Counting Tools

Are the following sets countable or uncountable? Please prove your claims.

<ul>

 <li><em>A</em>⇥<em>B</em>, where <em>A </em>and <em>B </em>are both countable.</li>

 <li>S<em>i</em><sub>2</sub><em>A </em><em>B<sub>i</sub></em>, where <em>A</em><em>,</em><em>B<sub>i </sub></em>are all countable.</li>

 <li>The set of all functions <em>f </em>from N to N such that <em>f </em>is non-decreasing. That is, <em>f</em>(<em>x</em>) <em>f</em>(<em>y</em>) whenever <em>x </em> <em>y</em>.</li>

 <li>The set of all functions <em>f </em>from N to N such that <em>f </em>is non-increasing. That is, <em>f</em>(<em>x</em>) <em>f</em>(<em>y</em>) whenever <em>x </em> <em>y</em>.</li>

 <li>The set of all bijective functions from N to N.</li>

</ul>

3       Impossible Programs

Show whether the following programs can exist or not.

<ul>

 <li>A program <em>P </em>that takes in any program <em>F</em>, input <em>x </em>and output <em>y </em>and returns true if <em>F</em>(<em>x</em>) outputs <em>y </em>and false otherwise.</li>

 <li>A program <em>P </em>that takes in two programs <em>F </em>and <em>G </em>and returns true if <em>F </em>and <em>G </em>halt on the same inputs, and false otherwise.</li>

</ul>

4      Undecided?

Let us think of a computer as a machine which can be in any of <em>n </em>states {<em>s</em><sup>1</sup><em>,…,</em><em>s<sup>n</sup></em>}. The state of a 10 bit computer might for instance be specified by a bit string of length 10, making for a total of 2<sup>10 </sup>states that this computer could be in at any given point in time. An algorithm <em>A </em>then is a list of <em>k </em>instructions (<em>i</em><sub>0</sub><em>,</em><em>i</em><sub>2</sub><em>,…,</em><em>i<sub>k </sub></em><sub>1</sub>), where each <em>i<sub>l </sub></em>is a function of a state <em>c </em>that returns another state <em>u </em>and a number <em>j</em>. Executing <em>A</em>(<em>x</em>) means computing

(<em>c</em>1<em>, </em><em>j</em>1)= <em>i</em>0(<em>x</em>)<em>,              </em>(<em>c</em>2<em>, </em><em>j</em>2)= <em>i</em><em>j</em><sub>1</sub>(<em>c</em>1)<em>,               </em>(<em>c</em>3<em>, </em><em>j</em>3)= <em>i</em><em>j</em><sub>2</sub>(<em>c</em>2)<em>,             …</em>

until <em>j</em><em><sub>`              </sub></em><em>k </em>for some <em>`</em>, at which point the algorithm halts and returns <em>c</em><em><sub>` </sub></em><sub>1</sub>.

<ul>

 <li>How many iterations can an algorithm of <em>k </em>instructions perform on an <em>n</em>-state machine (at most) without repeating any computation?</li>

 <li>Show that if the algorithm is still running after 2<em>n</em><sup>2</sup><em>k</em><sup>2 </sup>iterations, it will loop forever.</li>

 <li>Give an algorithm that decides whether an algorithm <em>A </em>halts on input <em>x </em>or not. Does your contruction contradict the undecidability of the halting problem?</li>

</ul>

5       Clothing Argument

<ul>

 <li>There are four categories of clothings (shoes, trousers, shirts, hats) and we have ten distinct items in each category. How many distinct outfits are there if we wear one item of each category?</li>

 <li>How many outfits are there if we wanted to wear exactly two categories?</li>

 <li>How many ways do we have of hanging four of our ten hats in a row on the wall? (Order matters.)</li>

 <li>We can pack four hats for travels. How many different possibilities for packing four hats are there? Can you express this number in terms of your answer to part (c)?</li>

 <li>If we have exactly 3 red hats, 3 green hats and 4 turquoise hats, and hats of the same colour are indistinguishable, how many distinct sets of three hats can we pack?</li>

</ul>

Before you start your homework, state briefly how you worked on it. Who else did you work with?

List names and email addresses. (In case of homework party, you can just describe the group.)

<h1>1         Counting, Counting, and More Counting</h1>

The only way to learn counting is to practice, practice, practice, so here is your chance to do so. For this problem, you do not need to show work that justifies your answers. We encourage you to leave your answer as an expression (rather than trying to evaluate it to get a specific number).

<ul>

 <li>How many ways are there to arrange <em>n </em>1s and <em>k </em>0s into a sequence?</li>

 <li>A bridge hand is obtained by selecting 13 cards from a standard 52-card deck. The order of the cards in a bridge hand is irrelevant.</li>

</ul>

How many different 13-card bridge hands are there? How many different 13-card bridge hands are there that contain no aces? How many different 13-card bridge hands are there that contain all four aces? How many different 13-card bridge hands are there that contain exactly 6 spades?

<ul>

 <li>Two identical decks of 52 cards are mixed together, yielding a stack of 104 cards. How many different ways are there to order this stack of 104 cards?</li>

 <li>How many 99-bit strings are there that contain more ones than zeros?</li>

 <li>An anagram of FLORIDA is any re-ordering of the letters of FLORIDA, i.e., any string made up of the letters F, L, O, R, I, D, and A, in any order. The anagram does not have to be an English word.</li>

</ul>

How many different anagrams of FLORIDA are there? How many different anagrams of ALASKA are there? How many different anagrams of ALABAMA are there? How many different anagrams of MONTANA are there?

<ul>

 <li>How many different anagrams of ABCDEF are there if: (1) C is the left neighbor of E; (2) C is on the left of E (and not necessarily E’s neighbor)</li>

 <li>We have 9 balls, numbered 1 through 9, and 27 bins. How many different ways are there to distribute these 9 balls among the 27 bins? Assume the bins are distinguishable (e.g., numbered 1 through 27).</li>

 <li>We throw 9 identical balls into 7 bins. How many different ways are there to distribute these 9 balls among the 7 bins such that no bin is empty? Assume the bins are distinguishable (e.g., numbered 1 through 7).</li>

 <li>How many different ways are there to throw 9 identical balls into 27 bins? Assume the bins are distinguishable (e.g., numbered 1 through 27).</li>

 <li>There are exactly 20 students currently enrolled in a class. How many different ways are there to pair up the 20 students, so that each student is paired with one other student?</li>

 <li>How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>+···+<em>x<sub>k </sub></em>= <em>n </em>have, if each <em>x </em>must be a non-negative integer? (l) How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>= <em>n </em>have, if each <em>x </em>must be a <em>strictly positive </em>integer?</li>

</ul>

(m) How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>+···+<em>x<sub>k </sub></em>= <em>n </em>have, if each <em>x </em>must be a <em>strictly positive </em>integer?

<h1>2       Binomial Beads</h1>

<ul>

 <li>Alistair is making school spirit keychains, which consist of a sequence of <em>n </em>beads on a string. He has blue beads and gold beads. How many unique keychains can he make with exactly <em>k </em>≤ <em>n </em>blue beads?</li>

 <li>Alistair decides to sell his keychains! He decides on the following pricing scheme:

  <ul>

   <li>Blue beads have a value of <em>x</em></li>

   <li>Gold beads have a value of <em>y</em></li>

   <li>The price of a keychain is the product of the values of all of its beads.</li>

  </ul></li>

</ul>

What is the price of a keychain with exactly <em>k </em>≤ <em>n </em>blue beads?

<ul>

 <li>Alistair decides to make exactly one of every possible unique keychain. If he sells every keychain he creates, how much revenue will he make? Use parts (a) and (b), and leave your answer in summation form.</li>

 <li>Draw a connection between part (c) and the binomial theorem.</li>

</ul>

(<em>x</em>+<em>y</em>)<em>n </em>= <em>x</em><em>k</em><em>y</em><em>n</em>−<em>k</em>

<em>Hint: How do you calculate the product (x + y)(x + y)?</em>

<h1>3     Minesweeper</h1>

Minesweeper is a game that takes place on a grid of squares. When you click a square, it disappears to reveal either an integer ∈ [1<em>,</em>8], a mine, or a blank space. If it reveals a mine, you instantly lose. If it reveals a number, that number refers to the number of mines adjacent to that square (including diagonally adjacent). If it reveals a blank space, there were 0 mines adjacent to it.

You are playing on a 8×8 board with 10 mines randomly distributed across the board. In your first move, you click a square near the center of the board.

<ul>

 <li>What is the probability that the square reveals…

  <ol>

   <li>a mine?</li>

   <li>a blank space?</li>

  </ol></li>

</ul>

<ul>

 <li>the number <em>k</em>?</li>

</ul>

<ul>

 <li>The first square you picked revealed the number <em>k</em>. For your next move, you want to minimize the probability of picking a mine. Should you pick a square adjacent to your first pick, or a different square? Your answer should depend on the value of <em>k</em>.</li>

 <li>Your first move resulted in the number 1. You pick the square to the right for your next move.</li>

</ul>

What is the probability that this square reveals the number 4?

<h1>4        Playing Strategically</h1>

Bob, Eve and Carol bought new slingshots. Bob is not very accurate hitting his target with probability 1<em>/</em>3. Eve is better, hitting her target with probability 2<em>/</em>3. Carol never misses. They decide to play the following game: They take turns shooting each other. For the game to be fair, Bob starts first, then Eve and finally Carol. Any player who gets shot has to leave the game. The last person standing wins the game. What is Bob’s best course of action regarding his first shot?

<ul>

 <li>Compute the probability of the event <em>E</em><sub>1 </sub>that Bob wins in a duel against Eve alone, assuming he shoots first.</li>

 <li>Compute the probability of the event <em>E</em><sub>2 </sub>that Bob wins in a duel against Eve alone, assuming he shoots second.</li>

 <li>Compute the probability of the same events for a duel of Bob against Carol.</li>

 <li>Assuming that both Eve and Carol play rationally, conclude that Bob’s best course of action is to shoot into the air (i.e., intentionally miss)! (Hint: What happens if Bob misses? What if he doesn’t?)</li>

</ul>

<h1>5      Weathermen</h1>

Tom is a weatherman in New York. On days when it snows, Tom correctly predicts the snow 70% of the time. When it doesn’t snow, he correctly predicts no snow 95% of the time. In New York, it snows on 10% of all days.

<ul>

 <li>If Tom says that it is going to snow, what is the probability it will actually snow?</li>

 <li>What is Tom’s overall accuracy?</li>

 <li>Tom’s friend Jerry is a weatherman in Alaska. Jerry claims that she is a better weatherman than Tom even though her overall accuracy is lower. After looking at their records, you determine that Jerry is indeed better than Tom at predicting snow on snowy days and sun on sunny days. How is this possible?</li>

</ul>

<em>Hint: what is the weather like in Alaska?</em>




<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

<ul>

 <li>(i) Let <em>X </em>∼ Bin(5<em>,</em>1<em>/</em>4). Let <em>Y </em>be a random variable equal to 5−<em>X</em>. What are the distributions of <em>X </em>and <em>Y</em>?</li>

</ul>

(ii) Let <em>Z </em>be a random variable denoting the result of a die roll (so 1 ≤ <em>Z </em>≤ 6 uniformly at random). What is E[<em>Z</em><sup>2</sup>]?

For each of the problems below, if you think the answer is “yes” then provide a proof. If you think the answer is “no”, then provide a counterexample.

<ul>

 <li>If <em>A </em>and <em>B </em>are integer-valued random variables such that for every integer <em>i</em>, P(<em>A </em>= <em>i</em>) = P(<em>B </em>=</li>

</ul>

<em>i</em>), then is P(<em>A </em>= <em>B</em>) <em>&gt; </em>0?

<ul>

 <li>If <em>C </em>is an integer-valued random variable, then is E[<em>C</em><sup>2</sup>] = E[<em>C</em>]<sup>2</sup>?</li>

 <li>If <em>X </em>and <em>Y </em>are random variables and E[<em>X</em>] <em>&gt; </em>100E[<em>Y</em>], then is P(<em>X </em><em>&gt;</em><em>Y</em>) <em>&gt; </em>1<em>/</em>100?</li>

 <li>If <em>X </em>and <em>Y </em>are random variables taking positive values, then is<em><sub>Y</sub></em><sub>]</sub>?</li>

 <li>If <em>A</em><em>,</em><em>B</em><em>,</em><em>C </em>are events such that P(<em>A</em>∩<em>B</em>∩<em>C</em>) = P(<em>A</em>)P(<em>B</em>)P(<em>C</em>), then are <em>A</em><em>,</em><em>B</em><em>,</em><em>C </em>mutually independent?</li>

 <li>Is an event <em>A </em>never independent with itself?</li>

 <li>If <em>A </em>and <em>B </em>are independent events, then are <em>A </em>and <em>B </em>independent?</li>

</ul>

<h1>2       Airport Revisited</h1>

<ul>

 <li>Suppose that there are <em>n </em>airports arranged in a circle. A plane departs from each airport, and randomly chooses an airport to its left or right to fly to. What is the expected number of empty airports after all planes have landed?</li>

 <li>Now suppose that we still have <em>n </em>airports, but instead of being arranged in a circle, they form a general graph, where each airport is denoted by a vertex, and an edge between two airports indicates that a flight is permitted between them. There is a plane departing from each airport and randomly chooses a neighboring destination where a flight is permitted. What is the expected number of empty airports after all planes have landed? (Express your answer in terms of <em>N</em>(<em>i</em>) – the set of neighboring airports of airport <em>i</em>, and deg(<em>i</em>) – the number of neighboring airports of airport <em>i</em>).</li>

</ul>

<h1>3      Fizzbuzz</h1>

<ul>

 <li>Fizzbuzz is a classic software engineering interview question. You are given a natural number <em>n</em>, and for each integer <em>i </em>from 1 to <em>n </em>you have to print either “fizzbuzz” if <em>i </em>is divisible by 15, “fizz” if <em>i </em>is divisible by 3 but not 15, “buzz” if <em>i </em>is divisible by 5 but not 15, or the integer itself if <em>i </em>is not divisible by 3 or 5.</li>

</ul>

If <em>n </em>is a multiple of 15, then how many printed lines will contain an integer?

(Hint: If you pick a line uniformly at random, then what is the probability that the printed line contains an integer?)

<ul>

 <li>Recall the Euler totient function from Homework 4:</li>

</ul>

<em>φ</em>(<em>n</em>) = |{<em>i </em>: 1 ≤ <em>i </em>≤ <em>n</em><em>,</em>gcd(<em>i</em><em>,</em><em>n</em>) = 1}|<em>.</em>

Suppose <em>n </em>= <em>p<sup>α</sup></em><sub>1</sub><sup>1</sup><em>p<sup>α</sup></em><sub>2</sub><sup>2 </sup>···<em>p<sup>α</sup><sub>k</sub></em><em><sup>k </sup></em>where <em>p</em><sub>1</sub><em>,</em><em>p</em><sub>2</sub><em>,…,</em><em>p<sub>k </sub></em>are distinct primes and <em>α</em><sub>1</sub><em>,</em><em>α</em><sub>2</sub><em>,…,</em><em>α<sub>k </sub></em>are positive integers. Prove that

<em>φ</em>(<em>n</em>)

<em>n </em>= ∏<em><sub>j</sub></em>

<h1>4        Cliques in Random Graphs</h1>

Consider a graph <em>G </em>= (<em>V</em><em>,</em><em>E</em>) on <em>n </em>vertices which is generated by the following random process: for each pair of vertices <em>u </em>and <em>v</em>, we flip a fair coin and place an (undirected) edge between <em>u </em>and <em>v </em>if and only if the coin comes up heads. So for example if <em>n </em>= 2, then with probability 1<em>/</em>2, <em>G </em>= (<em>V</em><em>,</em><em>E</em>) is the graph consisting of two vertices connected by an edge, and with probability 1<em>/</em>2 it is the graph consisting of two isolated vertices.

<ul>

 <li>What is the size of the sample space?</li>

 <li>A <em>k</em>-clique in graph is a set of <em>k </em>vertices which are pairwise adjacent (every pair of vertices is connected by an edge). For example a 3-clique is a triangle. What is the probability that a particular set of <em>k </em>vertices forms a <em>k</em>-clique?</li>

 <li>Prove that <em><sup>n</sup><sub>k</sub></em>.</li>

</ul>

<em>Optional: </em>Can you come up with a combinatorial proof? Of course, an algebraic proof would also get full credit.

<ul>

 <li>Prove that the probability that the graph contains a <em>k</em>-clique, for <em>k </em>≥ 4log<em>n</em>+1, is at most 1<em>/</em><em>n</em>. (The log is taken base 2).</li>

</ul>

<em>Hint: </em>Apply the union bound and part (c).

<h1>5          Balls and Bins, All Day Every Day</h1>

You throw <em>n </em>balls into <em>n </em>bins uniformly at random, where <em>n </em>is a positive <em>even </em>integer.

<ul>

 <li>What is the probability that exactly <em>k </em>balls land in the first bin, where <em>k </em>is an integer 0 ≤ <em>k </em>≤ <em>n</em>?</li>

 <li>What is the probability <em>p </em>that at least half of the balls land in the first bin? (You may leave your answer as a summation.)</li>

 <li>Using the union bound, give a simple upper bound, in terms of <em>p</em>, on the probability that some bin contains at least half of the balls.</li>

 <li>What is the probability, in terms of <em>p</em>, that at least half of the balls land in the first bin, or at least half of the balls land in the second bin?</li>

 <li>After you throw the balls into the bins, you walk over to the bin which contains the first ball you threw, and you randomly pick a ball from this bin. What is the probability that you pick up the first ball you threw? (Again, leave your answer as a summation.)</li>

</ul>

Sundry

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

Mr. and Mrs. Brown decide to continue having children until they either have their first girl or until they have three children. Assume that each child is equally likely to be a boy or a girl, independent of all other children, and that there are no multiple births. Let <em>G </em>denote the numbers of girls that the Browns have. Let <em>C </em>be the total number of children they have.

<ul>

 <li>Determine the sample space, along with the probability of each sample point.</li>

 <li>Compute the joint distribution of <em>G </em>and <em>C</em>. Fill in the table below.</li>

</ul>

<table width="265">

 <tbody>

  <tr>

   <td width="68"> </td>

   <td width="67"><em>C</em>=1</td>

   <td width="65"><em>C</em>=2</td>

   <td width="65"><em>C</em>=3</td>

  </tr>

  <tr>

   <td width="68"><em>G</em>=0</td>

   <td width="67"> </td>

   <td width="65"> </td>

   <td width="65"> </td>

  </tr>

  <tr>

   <td width="68"><em>G</em>=1</td>

   <td width="67"> </td>

   <td width="65"> </td>

   <td width="65"> </td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use the joint distribution to compute the marginal distributions of <em>G </em>and <em>C </em>and confirm that the values are as you’d expect. Fill in the tables below.</li>

</ul>

<table width="439">

 <tbody>

  <tr>

   <td width="160">


    <table width="155">

     <tbody>

      <tr>

       <td width="95">P(<em>G</em>=0)</td>

       <td width="60"> </td>

      </tr>

      <tr>

       <td width="95">P(<em>G</em>=1)</td>

       <td width="60"> </td>

      </tr>

     </tbody>

    </table></td>

   <td width="279">


    <table width="274">

     <tbody>

      <tr>

       <td width="91">P(<em>C</em>=1)</td>

       <td width="91">P(<em>C</em>=2)</td>

       <td width="91">P(<em>C</em>=3)</td>

      </tr>

      <tr>

       <td width="91"> </td>

       <td width="91"> </td>

       <td width="91"> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Are <em>G </em>and <em>C </em>independent?</li>

 <li>What is the expected number of girls the Browns will have? What is the expected number of children that the Browns will have?</li>

</ul>

CS 70, Fall 2018, HW 10                                                                                                                                                                        1

2        Will I Get My Package?

A delivery guy in some company is out delivering <em>n </em>packages to <em>n </em>customers, where <em>n</em>∈N, <em>n </em><em>&gt; </em>1. Not only does he hand a random package to each customer, he opens the package before delivering it with probability 1<em>/</em>2. Let <em>X </em>be the number of customers who receive their own packages unopened.

<ul>

 <li>Compute the expectation E(<em>X</em>).</li>

 <li>Compute the variance var(<em>X</em>).</li>

</ul>

3         Double-Check Your Intuition Again

<ul>

 <li>You roll a fair six-sided die and record the result <em>X</em>. You roll the die again and record the result <em>Y</em>.

  <ul>

   <li>What is cov(<em>X</em>+<em>Y</em><em>,</em><em>X</em>−<em>Y</em>)?</li>

   <li>Prove that <em>X</em>+<em>Y </em>and <em>X</em>−<em>Y </em>are not independent.</li>

  </ul></li>

</ul>

For each of the problems below, if you think the answer is “yes” then provide a proof. If you think the answer is “no”, then provide a counterexample.

<ul>

 <li>If <em>X </em>is a random variable and var(<em>X</em>)= 0, then must <em>X </em>be a constant?</li>

 <li>If <em>X </em>is a random variable and <em>c </em>is a constant, then is var(<em>cX</em>)=<em>c</em>var(<em>X</em>)?</li>

 <li>If <em>A </em>and <em>B </em>are random variables with nonzero standard deviations and Corr(<em>A</em><em>,</em><em>B</em>)= 0, then are <em>A </em>and <em>B </em>independent?</li>

 <li>If <em>X </em>and <em>Y </em>are not necessarily independent random variables, but Corr(<em>X</em><em>,</em><em>Y</em>)= 0, and <em>X </em>and <em>Y </em>have nonzero standard deviations, then is var(<em>X</em>+<em>Y</em>)= var(<em>X</em>)+var(<em>Y</em>)?</li>

 <li>If <em>X </em>and <em>Y </em>are random variables then is E(max(<em>X</em><em>,</em><em>Y</em>)min(<em>X</em><em>,</em><em>Y</em>))=E(<em>XY</em>)?</li>

 <li>If <em>X </em>and <em>Y </em>are independent random variables with nonzero standard deviations, then is</li>

</ul>

Corr(max(<em>X</em><em>,</em><em>Y</em>)<em>,</em>min(<em>X</em><em>,</em><em>Y</em>))= Corr(<em>X</em><em>,</em><em>Y</em>)?

<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

Cuckoo birds are parasitic beasts. They are known for hijacking the nests of other bird species and evicting the eggs already inside. Cuckoo hashing is inspired by this behavior. In cuckoo hashing, when we get a collision, the element that was already there gets evicted and rehashed.

We study a simple (but ineffective, as we’ll see) version of cuckoo hashing, where all hashes are random. Let’s say we want to hash <em>n </em>pieces of data <em>D</em><sub>1</sub><em>,</em><em>D</em><sub>2</sub><em>,…,</em><em>D<sub>n </sub></em>into <em>n </em>possible hash buckets labeled 1<em>,…,</em><em>n</em>. We hash the <em>D</em><sub>1</sub><em>,…,</em><em>D<sub>n </sub></em>in that order. When hashing <em>D<sub>i</sub></em>, we assign it a random bucket chosen uniformly from 1<em>,…,</em><em>n</em>. If there is no collision, then we place <em>D<sub>i </sub></em>into that bucket. If there is a collision with some other <em>D<sub>j</sub></em>, we evict <em>D<sub>j </sub></em>and assign it another random bucket uniformly from 1<em>,…,</em><em>n</em>. (It is possible that <em>D<sub>j </sub></em>gets assigned back to the bucket it was just evicted from!) We again perform the eviction step if we get another collision. We keep doing this until there is no more collision, and we then introduce the next piece of data, <em>D<sub>i</sub></em><sub>+</sub><sub>1 </sub>to the hash table.

<ul>

 <li>What is the probability that there are no collisions over the entire process of hashing <em>D</em><sub>1</sub><em>,…,</em><em>D<sub>n </sub></em>to buckets 1<em>,…,</em><em>n</em>? What value does the probability tend towards as <em>n </em>grows very large?</li>

 <li>Assume we have already hashed <em>D</em><sub>1</sub><em>,…,</em><em>D<sub>n</sub></em><sub>−</sub><sub>1</sub>, and they each occupy their own bucket. We now introduce <em>D<sub>n </sub></em>into our hash table. What is the expected number of collisions that we’ll see while hashing <em>D<sub>n</sub></em>? (<em>Hint</em>: What happens when we hash <em>D<sub>n </sub></em>and get a collision, so we evict some other <em>D<sub>i </sub></em>and have to hash <em>D<sub>i</sub></em>? Are we at a situation that we’ve seen before?)</li>

</ul>

<h1>2         Markov’s Inequality and Chebyshev’s Inequality</h1>

A random variable <em>X </em>has variance var(<em>X</em>) = 9 and expectation E[<em>X</em>] = 2. Furthermore, the value of <em>X </em>is never greater than 10. Given this information, provide either a proof or a counterexample for the following statements.

<ul>

 <li>P[<em>X </em>≤ 1] ≤ 8<em>/</em></li>

 <li>P[<em>X </em>≥ 6] ≤ 9<em>/</em></li>

 <li>P[<em>X </em>≥ 6] ≤ 9<em>/</em></li>

</ul>

<h1>3       Easy A’s</h1>

A friend tells you about a course called “Laziness in Modern Society” that requires almost no work. You hope to take this course next semester to give yourself a well-deserved break after working hard in CS 70. At the first lecture, the professor announces that grades will depend only on two homework assignments. Homework 1 will consist of three questions, each worth 10 points, and Homework 2 will consist of four questions, also each worth 10 points. He will give an A to any student who gets at least 60 of the possible 70 points.

However, speaking with the professor in office hours you hear some very disturbing news. He tells you that, in the spirit of the class, the GSIs are very lazy, and to save time the grading will be done as follows. For each student’s Homework 1, the GSIs will choose an integer randomly from a distribution with mean <em>µ </em>= 5 and variance <em>σ</em><sup>2 </sup>= 1. They’ll mark each of the three questions with that score. To grade Homework 2, they’ll again choose a random number from the same distribution, independently of the first number, and will mark all four questions with that score.

If you take the class, what will the mean and variance of your total class score be? Use Chebyshev’s inequality to conclude that you have less than a 5% chance of getting an A when the grades are randomly chosen this way.

<h1>4       Confidence Interval Introduction</h1>

We observe a random variable <em>X </em>which has mean <em>µ </em>and standard deviation <em>σ </em>∈ (0<em>,</em>∞). Assume that the mean <em>µ </em>is unknown, but <em>σ </em>is known.

We would like to give a 95% confidence interval for the unknown mean <em>µ</em>. In other words, we want to give a random interval (<em>a</em><em>,</em><em>b</em>) (it is random because it depends on the random observation <em>X</em>) such that the probability that <em>µ </em>lies in (<em>a</em><em>,</em><em>b</em>) is at least 95%.

We will use a confidence interval of the form (<em>X </em>−<em>ε</em><em>,</em><em>X </em>+<em>ε</em>), where <em>ε </em><em>&gt; </em>0 is the width of the confidence interval. When <em>ε </em>is smaller, it means that the confidence interval is narrower, i.e., we are giving a more <em>precise </em>estimate of <em>µ</em>.

<ul>

 <li>Using Chebyshev’s Inequality, calculate an upper bound on P{|<em>X </em>−<em>µ</em>| ≥ <em>ε</em>}.</li>

 <li>Explain why P{|<em>X </em>−<em>µ</em>| <em>&lt; </em><em>ε</em>} is the same as P{<em>µ </em>∈ (<em>X </em>−<em>ε</em><em>,</em><em>X </em>+<em>ε</em>)}.</li>

 <li>Using the previous two parts, choose the width of the confidence interval <em>ε </em>to be large enough so that P{<em>µ </em>∈ (<em>X </em>−<em>ε</em><em>,</em><em>X </em>+<em>ε</em>)} is guaranteed to exceed 95%.</li>

</ul>

[Note: Your confidence interval is allowed to depend on <em>X</em>, which is observed, and <em>σ</em>, which is known. Your confidence interval is not allowed to depend on <em>µ</em>, which is unknown.]

<ul>

 <li>The previous three parts dealt with the case when you observe one sample <em>X</em>. Now, let <em>n </em>be a positive integer and let <em>X</em><sub>1</sub><em>,…,</em><em>X<sub>n </sub></em>be i.i.d. samples, each with mean <em>µ </em>and standard deviation <em>σ </em>∈ (0<em>,</em>∞). As before, assume that <em>µ </em>is unknown but <em>σ </em>is known.</li>

</ul>

Here, a good estimator for <em>µ </em>is the <em>sample mean X</em>¯ := <em>n</em><sup>−</sup><sup>1 </sup><sub>∑</sub><em><sup>n</sup></em><em><sub>i</sub></em><sub>=</sub><sub>1 </sub><em>X<sub>i</sub></em>. Calculate the mean and variance of <em>X</em>¯.

<ul>

 <li>We will now use a confidence interval of the form (<em>X</em>¯ −<em>ε</em><em>,</em><em>X</em>¯ +<em>ε</em>) where <em>ε </em><em>&gt; </em>0 again represents the width of the confidence interval. Imitate the steps of (a) through (c) to choose the width <em>ε </em>to be large enough so that P{<em>µ </em>∈ (<em>X</em>¯ −<em>ε</em><em>,</em><em>X</em>¯ +<em>ε</em>)} is guaranteed to exceed 95%.</li>

</ul>

To check your answer, your confidence interval should be <em>smaller </em>when <em>n </em>is larger. Intuitively, if you collect more samples, then you should be able to give a more <em>precise </em>estimate of <em>µ</em>.

<h1></h1>

<h1>Due: Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

It’s that time of the year again – Safeway is offering its Monopoly Card promotion. Each time you visit Safeway, you are given one of <em>n </em>different Monopoly Cards with equal probability. You need to collect them all to redeem the grand prize.

Let <em>X </em>be the number of visits you have to make before you can redeem the grand prize. Show that

<em> [Hint: Does this remind you of a particular problem? What is the</em>

<em>expectation for this problem?]</em>

<h1>2       Geometric Distribution</h1>

Two faulty machines, <em>M</em><sub>1 </sub>and <em>M</em><sub>2</sub>, are repeatedly run synchronously in parallel (i.e., both machines execute one run, then both execute a second run, and so on). On each run, <em>M</em><sub>1 </sub>fails with probability <em>p</em><sub>1 </sub>and <em>M</em><sub>2 </sub>fails with probability <em>p</em><sub>2</sub>, all failure events being independent. Let the random variables <em>X</em><sub>1</sub>, <em>X</em><sub>2 </sub>denote the number of runs until the first failure of <em>M</em><sub>1</sub>, <em>M</em><sub>2 </sub>respectively; thus <em>X</em><sub>1</sub>, <em>X</em><sub>2 </sub>have geometric distributions with parameters <em>p</em><sub>1</sub>, <em>p</em><sub>2 </sub>respectively. Let <em>X </em>denote the number of runs until the first failure of <em>either </em>machine.

<ul>

 <li>Show that <em>X </em>also has a geometric distribution, with parameter <em>p</em><sub>1 </sub>+ <em>p</em><sub>2 </sub>− <em>p</em><sub>1</sub><em>p</em><sub>2</sub>.</li>

 <li>Now, two technicians are hired to check on the machines every run. They decide to take turns checking on the machines every hour. What is the probability that the first technician is the first one to find a faulty machine?</li>

</ul>

CS 70, Fall 2018, HW 12                                                                                                                                                                        1

<h1>3       Geometric and Poisson</h1>

Let <em>X </em>be geometric with parameter <em>p</em>,<em>Y </em>be Poisson with parameter <em>λ</em>, and <em>Z </em>= max(<em>X</em><em>,</em><em>Y</em>). Assume <em>X </em>and <em>Y </em>are independent. For each of the following parts, your final answers should not have summations.

(a) Compute <em>P</em>(<em>X </em><em>&gt;</em><em>Y</em>). (b) Compute <em>P</em>(<em>Z </em>≥ <em>X</em>).

(c) Compute <em>P</em>(<em>Z </em>≤<em>Y</em>).

<h1>4      Darts</h1>

Alvin is playing darts. His aim follows an exponential distribution; that is, the probability density that the dart is <em>x </em>distance from the center is <em>f<sub>X</sub></em>(<em>x</em>) = exp(−<em>x</em>). The board’s radius is 4 units.

<ul>

 <li>What is the probability the dart will stay within the board?</li>

 <li>Say you know Alvin made it on the board. What is the probability he is within 1 unit from the center?</li>

 <li>If Alvin is within 1 unit from the center, he scores 4 points, if he is within 2 units, he scores 3, etc. In other words, Alvin scores b5−<em>x</em>c, where <em>x </em>is the distance from the center. What is Alvin’s expected score after one throw?</li>

</ul>

<h1>5       Exponential Practice</h1>

<ul>

 <li>Let <em>X</em><sub>1</sub><em>,</em><em>X</em><sub>2 </sub>∼ Exponential(<em>λ</em>) be independent, <em>λ </em><em>&gt; </em> Calculate the density of <em>Y </em>:= <em>X</em><sub>1 </sub>+<em>X</em><sub>2</sub>. [<em>Hint</em>: One way to approach this problem would be to compute the CDF of <em>Y </em>and then differentiate the CDF.]</li>

 <li>Let <em>t </em><em>&gt; </em> What is the density of <em>X</em><sub>1</sub>, conditioned on <em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>= <em>t</em>? [<em>Hint</em>: Once again, it may be helpful to consider the CDF P(<em>X</em><sub>1 </sub>≤ <em>x </em>| <em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>= <em>t</em>). To tackle the conditioning part, try conditioning instead on the event {<em>X</em><sub>1 </sub>+<em>X</em><sub>2 </sub>∈ [<em>t</em><em>,</em><em>t </em>+<em>ε</em>]}, where <em>ε </em><em>&gt; </em>0 is small.]</li>

</ul>

<h1>6      Uniform Means</h1>

Let <em>X</em><sub>1</sub><em>,</em><em>X</em><sub>2</sub><em>,…,</em><em>X<sub>n </sub></em>be <em>n </em>independent and identically distributed uniform random variables on the interval [0<em>,</em>1] (where <em>n </em>is a positive integer).

<ul>

 <li>Let <em>Y </em>= min{<em>X</em><sub>1</sub><em>,</em><em>X</em><sub>2</sub><em>,…,</em><em>X<sub>n</sub></em>}. Find E(<em>Y</em>). [<em>Hint</em>: Use the tail sum formula, which says the expected value of a nonnegative random variable isd<em>x</em>. Note that we can use the tail sum formula since <em>Y </em>≥ ]</li>

 <li>Let <em>Z </em>= max{<em>X</em><sub>1</sub><em>,</em><em>X</em><sub>2</sub><em>,…,</em><em>X<sub>n</sub></em>}. Find E(<em>Z</em>). [<em>Hint</em>: Find the CDF.]</li>

</ul>

<h1>Sundry</h1>

Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

In this problem, we will consider Buffon’s Needle, but with a catch. We now drop a needle at random onto a large grid, and example of which is shown below.

The length of the needle is 1, and the space between the grid lines is 1 as well.

Recall from class that a random throw means that the position of the center of the needle and its orientation are independent and uniformly distributed.

<ul>

 <li>Given that the angle between the needle and the horizontal lines is <em>θ</em>, what is the probability that the needle does not intersect any grid lines? Justify your answer.</li>

 <li>Continue part (a) to find the probability that the needle, when dropped onto the grid at random (with the angle chosen uniformly at random), intersects a grid line. Justify your answer.</li>

</ul>

<em>Hint: </em>You may use the fact that sin<em>θ </em>cos<em>θ </em>=  sin(2<em>θ</em>) without proof.

<ul>

 <li>Let <em>X </em>be the number of times the needle intersects a gridline (so, in the example shown above, <em>X </em>= 2). Find E[<em>X</em>]. Justify your answer.</li>

</ul>

<em>Hint: </em>Can you do this without using your answer from part (b)?

<ul>

 <li>Combine the previous parts to figure out the probability that <em>X </em>= 1, i.e. the needle will only intersects one gridline. Justify your answer.</li>

 <li>We will fold the needle into an equilateral triangle, where each side is length . What is the expected number of intersections that this triangle will have with the gridlines, when dropped onto the grid? Justify your answer.</li>

</ul>

<h1>2         Variance of the Minimum of Uniform Random Variables</h1>

i.i.d.

Let <em>n </em>be a positive integer and let <em>X</em><sub>1</sub><em>,…,</em><em>X<sub>n </sub></em>∼ Uniform[0<em>,</em>1]. Find var<em>Y</em>, where

<em>Y </em>:= min{<em>X</em><sub>1</sub><em>,…,</em><em>X<sub>n</sub></em>}<em>.</em>

<em>Hint</em>: You may need to perform integration by parts.

<h1>3         Erasures, Bounds, and Probabilities</h1>

Alice is sending 1000 bits to Bob. The probability that a bit gets erased is <em>p</em>, and the erasure of each bit is independent of the others.

Alice is using a scheme that can tolerate up to one-fifth of the bits being erased. That is, as long as Bob receives at least 801 of the 1000 bits correctly, he can decode Alice’s message.

In other words, Bob becomes unable to decode Alice’s message only if 200 or more bits are erased. We call this a “communication breakdown”, and we want the probability of a communication breakdown to be at most 10<sup>−</sup><sup>6</sup>.

<ol>

 <li>Use Markov’s inequality to upper bound <em>p </em>such that the probability of a communications breakdown is at most 10<sup>−</sup><sup>6</sup>.</li>

 <li>Use Chebyshev’s inequality to upper bound <em>p </em>such that the probability of a communications breakdown is at most 10<sup>−</sup><sup>6</sup>.</li>

 <li>As the CLT would suggest, approximate the fraction of erasures by a Gaussian random variable (with suitable mean and variance). Use this to find an approximate bound for <em>p </em>such that the probability of a communications breakdown is at most 10<sup>−</sup><sup>6</sup>.</li>

</ol>

<h1>4         Sampling a Gaussian With Uniform</h1>

In this question, we will see one way to generate a normal random variable if we have access to a random number generator that outputs numbers between 0 and 1 uniformly at random.

As a general comment, remember that showing two random variables have the same CDF or PDF is sufficient for showing that they have the same distribution.

<ul>

 <li>First, let us see how to generate an exponential random variable with a uniform random variable. Let <em>U</em><sub>1 </sub>∼<em>Uniform</em>(0<em>,</em>1). Prove that −ln<em>U</em><sub>1 </sub>∼ <em>Expo</em>(1).</li>

 <li>Let <em>N</em><sub>1</sub><em>,</em><em>N</em><sub>2 </sub>∼ <em>N </em>(0<em>,</em>1), where <em>N</em><sub>1 </sub>and <em>N</em><sub>2 </sub>are independent. Prove that <em>N</em>.</li>

</ul>

<em>Hint: </em>You may use the fact that over a region <em>R</em>, if we convert to polar coordinates (<em>x</em><em>,</em><em>y</em>) → (<em>r</em><em>,</em><em>θ</em>), then the double integral over the region <em>R </em>will be

ZZ    ZZ <em>f</em>(<em>x</em><em>,</em><em>y</em>)<em>dxdy </em>=           <em>f</em>(<em>r</em>cos<em>θ</em><em>,</em><em>r</em>sin<em>θ</em>)·<em>rdrdθ</em><em>.</em>

<em>R                                      R</em>

<ul>

 <li>Suppose we have two uniform random variables, <em>U</em><sub>1 </sub>and <em>U</em><sub>2</sub>. How would you transform these two random variables into a normal random variable with mean 0 and variance 1?</li>

</ul>

<em>Hint: </em>What part (b) tells us is that the point (<em>N</em><sub>1</sub><em>,</em><em>N</em><sub>2</sub>) will have a distance from the origin that is distributed as the square root of an exponential distribution. Try to use<em>U</em><sub>1 </sub>to sample the radius, and then use <em>U</em><sub>2 </sub>to sample the angle.

<h1>5        Markov Chain Terminology</h1>

In this question, we will walk you through terms related to Markov chains.

<ol>

 <li>(Irreducibility) A Markov chain is irreducible if, starting from any state <em>i</em>, the chain can transition to any other state <em>j</em>, possibly in multiple steps.</li>

 <li>(Periodicity) <em>d</em>(<em>i</em>) := gcd{<em>n</em><em>&gt; </em>0 |<em>P<sup>n</sup></em>(<em>i</em><em>,</em><em>i</em>)=P[<em>X<sub>n </sub></em>=<em>i</em>|<em>X</em><sub>0 </sub>=<em>i</em>]<em>&gt; </em>0}, <em>i</em>∈<em>X </em>. If <em>d</em>(<em>i</em>)= 1 ∀<em>i</em>∈<em>X </em>, then the Markov chain is aperiodic; otherwise it is periodic.</li>

 <li>(Matrix Representation) Define the transition probability matrix <em>P </em>by filling entry (<em>i</em><em>, </em><em>j</em>) with probability <em>P</em>(<em>i</em><em>, </em><em>j</em>).</li>

 <li>(Invariance) A distribution <em>π </em>is invariant for the transition probability matrix <em>P </em>if it satisfies the following balance equations: <em>π </em>= <em>πP</em>.</li>

</ol>

<em>a</em>

1−<em>b</em>1−<em>a</em>

<em>b</em>

<ul>

 <li>For what values of <em>a </em>and <em>b </em>is the above Markov chain irreducible? Reducible?</li>

 <li>For <em>a </em>= 1, <em>b </em>= 1, prove that the above Markov chain is periodic.</li>

 <li>For 0 <em>&lt; </em><em>a </em><em>&lt; </em>1, 0 <em>&lt; </em><em>b </em><em>&lt; </em>1, prove that the above Markov chain is aperiodic.</li>

 <li>Construct a transition probability matrix using the above Markov chain.</li>

 <li>Write down the balance equations for this Markov chain and solve them. Assume that the Markov chain is irreducible.</li>

</ul>

<h1>6        Analyze a Markov Chain</h1>

Consider the Markov chain <em>X</em>(<em>n</em>) with the state diagram shown below where <em>a</em><em>,</em><em>b </em>∈ (0<em>,</em>1).

<em>a               b</em>

<em>1 – a </em>

<em>0   1 – b     1      1      2</em>

<ul>

 <li>Show that this Markov chain is aperiodic;</li>

 <li>Calculate P[<em>X</em>(1) = 1<em>,</em><em>X</em>(2) = 0<em>,</em><em>X</em>(3) = 0<em>,</em><em>X</em>(4) = 1 | <em>X</em>(0) = 0];</li>

 <li>Calculate the invariant distribution;</li>

 <li>Let <em>T<sub>i </sub></em>= min{<em>n </em>≥ 0 | <em>X</em>(<em>n</em>) = <em>i</em>}, <em>T<sub>i </sub></em>is the number of steps until we transit to state <em>i </em>for the first time. Calculate E[<em>T</em><sub>2 </sub>| <em>X</em>(0) = 1].</li>

</ul>

<h1>7       Boba in a Straw</h1>

Imagine that Jonathan is drinking milk tea and he has a very short straw: it has enough room to fit two boba (see figure).

<table width="57">

 <tbody>

  <tr>

   <td width="57"></td>

  </tr>

  <tr>

   <td width="57"> </td>

  </tr>

 </tbody>

</table>

Figure 1: A straw with one boba currently inside. The straw only has enough room to fit two boba.

Here is a formal description of the drinking process: We model the straw as having two “components” (the top component and the bottom component). At any given time, a component can contain nothing, or one boba. As Jonathan drinks from the straw, the following happens every second:

<ol>

 <li>The contents of the top component enter Jonathan’s mouth.</li>

 <li>The contents of the bottom component move to the top component.</li>

 <li>With probability <em>p</em>, a new boba enters the bottom component; otherwise the bottom component is now empty.</li>

</ol>

Help Jonathan evaluate the consequences of his incessant drinking!

<ul>

 <li>At the very start, the straw starts off completely empty. What is the expected number of seconds that elapse before the straw is completely filled with boba for the first time? [Write down the equations; you do not have to solve them.]</li>

 <li>Consider a slight variant of the previous part: now the straw is narrower at the bottom than at the top. This affects the drinking speed: if either (i) a new boba is about to enter the bottom component or (ii) a boba from the bottom component is about to move to the top component, then the action takes two seconds. If both (i) and (ii) are about to happen, then the action takes three seconds. Otherwise, the action takes one second. Under these conditions, answer the previous part again. [Write down the equations; you do not have to solve them.]</li>

 <li>Jonathan was annoyed by the straw so he bought a fresh new straw (the straw is no longer narrow at the bottom). What is the long-run average rate of Jonathan’s calorie consumption? (Each boba is roughly 10 calories.)</li>

 <li>What is the long-run average number of boba which can be found inside the straw? [Maybe you should first think about the long-run distribution of the number of boba.]</li>

</ul>