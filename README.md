## Impossible/Sum+Product Puzzle

Using Prolog to solve the Impossible Puzzle (as part of [CM20214](http://www.bath.ac.uk/catalogues/2014-2015/cm/CM20214.html): *Advanced Programming Principles*).

Built-in predicates will solve this puzzle in far fewer lines with Prolog. The specification for this assignment therefore rewarded a solution with as few inferences as possible (consequently resulting in a rather large number of base cases for merge sorting). Graded as a strong first.

### The Puzzle

Let X and Y be two integers with 1 < X < Y and X + Y ≤ 100. The mathematician S is given their sum X + Y and the mathematician P is given their product XY . The following conversation takes place:
* P: I do not know the two numbers.
* S: I knew you didn’t know. I don’t know either.
* P: Now I know the two numbers.
* S: Now I know the two numbers.

What are the numbers?
