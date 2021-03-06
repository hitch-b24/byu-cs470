# Simulated Annealing Algorithm Minilab
### CS 470 - BYU

**Point value:** 5 points
**Due Date:** Nov 15, 2017

*This lab has been adapted (a lot) from an assignment given at Harvard:
http://www.people.fas.harvard.edu/~albert/cscie220/Asst7.pdf*

#### Description
Write code for a simulated annealing algorithm to solve the Knapsack Problem:. 
Briefly stated, the Knapsack
Problem is as follows:

You have a collection of N objects of different weights, w1, w2, …, wn, and different
values, v1, v2, …, vn, and a knapsack that can only hold a certain maximum combined
weight W. You would like to get a set of objects of maximal value into the knapsack.

As a search problem, the knapsack problem turns out to be intractable – there is no way to search
efficiently, reducing the search to an exhaustive check of all possible combinations of objects,
and the time to solve it grows exponentially with the number of objects.

Simulated annealing, however, can more quickly find solutions that come extremely close to the
maximum, while not guaranteed to actually be the maximum. A brief overview of simulated
annealing is found in Section 4.1.2 of your textbook. Read up on exactly how to implement
simulated annealing (you may need to use online resources to get a detailed description), and
then code it up. Try it out on this test file (the format is a little strange, but you should be able to
figure it out easily)

#### Deliverables
Create a short write-up that documents the parameters you used in your algorithm. Document
the variations you used and how these variations impacted solution quality. Submit this write-up
with your code and the answer to the solution you get on the test file.

#### Scoring
+3 points for coding up a simulated annealing algorithm

+2 point for exploring how variations of the algorithm impact solution quality 
