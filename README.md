# CSCI-GA.1180-001-Homework-Assignment-3-solution

Download Here: [CSCI-GA.1180-001 Homework Assignment 3 solution](https://jarviscodinghub.com/assignment/csci-ga-1180-001-homework-assignment-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Exercise 3.1. [Matrix norms.] Consider the matrix
A =

1 −2
1 −1
!
.
(a) Give the value of kAk1 and the value of kAk∞.
(b) Find a 2-vector u such that kuk1 = 1 and kAuk1 = kAk1.
(c) Find a 2-vector v such that kvk∞ = 1 and kAvk∞ = kAk∞.
Exercise 3.2. Given a nonsingular matrix A and a vector b, let x denote the exact solution of Ax = b,
and let k·k denote any subordinate norm. Consider a matrix A such that kAk = 1 and a vector b such that
kbk = 10−6
. If kxk = 1, what do we know about cond(A) measured in the given norm? Explain.
Exercise 3.3. Note: numerical calculations (using the two-norm) will be needed to solve this problem.
Let
A =

0.625 0.4376
0.546 0.3823 !
and b =

1.0626
0.9283 !
.
(a) Show that the exact solution x
∗
to Ax = b is x
∗ = (1, 1)T
.
(b) Give the solution xe computed by executing the Matlab “backslash” command A\b (or the equivalent in
octave or SciPy). Compute and print the vectors (i) d = xe− x
∗
, (ii) r
∗ = b − Ax∗
, and (iii) re = b − Axe.
Comment on the relative size of their norms.
(c) Let xb be a potential solution of Ax = b, with residual rb = b − Axb, and define E as the rank-one matrix
E =
1
xb
T xb
rbxb
T
. (1)
Show mathematically that the exact matrix E defined in (1) satisfies the relation
(A + E)xb = b.
(d) Consider the specific vector xb
xb =

−27.678
41.958 !
.
Would you say that xb is close to x
∗
from (a)? Would you say that xb is close to xe from (b)? Explain.
2
(e) Given the vector xb from (d), compute and print (i) its residual rb = b − Axb, (ii) the matrix E from (1),
and (iii) kEk2. Would you describe kEk2 as “small” or “large”? Explain.
(f) Compute the solution ¯x to (A + E) ¯x = b, using the Matlab backslash command, and print ¯x.
(g) Print kx¯ − xbk. Based on this norm, is ¯x “close to” xb from part (d)? Explain why or why not.
(h) Do you agree with the statement that xb is close to the exact solution of a system that is close to the
original system? Explain why or why not.
Exercise 3.4.
(a) Show that, if the square matrices B and C are nonsingular, then cond(BC) ≤ cond(B) cond(C), where
the condition number is measured in any of the “standard” matrix norms (one, two, or infinity).
(b) Show that, measured in the matrix two-norm, cond(AT
) = cond(A).
(c) If cond is measured in the matrix one-norm (the maximum absolute column sum), is cond(AT
) necessarily equal to cond(A)? Explain your answer, giving a specific example for illustration if your answer
is “no”.
Exercise 3.5. Consider the following matrix A and vector b:
A =


2 4
1 2
1 2

 , b =


3
2
1

 .
(a) What is the rank of A?
(b) Give a general form, expressed in terms of a single scalar, for any vector in the range of A.
(c) Explain why the dimension of the null space of AT
is two, and display two linearly independent vectors
z1 and z2 in the null space of AT
. Give a general form, expressed in terms of two scalars, for every
vector z in null(AT
), i.e., such that AT
z = 0.
(d) Given the particular vector b, find the specific vectors bR ∈ range(A) (i.e., the range-space component
of b) and bN ∈ null(AT
) such that b = bR + bN .
(e) What is the dimension of the null space of A? (Note: of A, not AT
.) What is the general form of any
vector q = (q1, q2)
T
such that Aq = 0?
(f) Find a specific two-vector v = (α1, α2)
T
such that Av = bR, where bR is the vector found in part (d).
(In this part, give numbers for the components of vb.)
(g) Consider a two-vector bA defined as bA = v + q, where Av = bR from part (d) and Aq = 0, and use this
form to obtain two specific (different) instances of bA (i.e., with numbers).

