# algo-proj2
Project 2 of COT4400, Analysis of Algorithms. This purpose of this project was to showcase our ability to use memoization and dynamic programming. The only purpose of this repository is to showcase said skills and for no reason, should anyone plagiarize the code.

For this project, you will develop two algorithms to evaluate the cost to produce two kinds of
products. Designing and implementing these algorithms will require you to model the problem
using dynamic programming, then understand and implement your model.

For an omnidroid, the second line of the robot specification will have two positive integers n and
m, indicating the number of parts in the assembly and the number of assembly dependencies,
respectively. The next m lines will have two nonnegative integers i and j, representing that part i
is used in the assembly of part j. For convenience, the parts are numbered 0 to n − 1 instead of
being identified by names like “Emote-o-tron”, with part n − 1 representing the finished omnidroid.
Every intermediate part will appear as the second entry in at least one line, while basic parts will
not appear as the second entry in a line. The n lines following the part dependencies will have a
single integer indicating how many sprockets are used to create an omnidroid part outside of any
other parts used in the construction (in order, part 0 to part n − 1).

For a robotomaton, the second line will have a positive integer n representing the number of stages
in the construction (with the last stage being the completed robotomaton). The following n lines
will have two nonnegative integers, s and p, representing the number of sprockets needed for this
stage and the number of previous stages that are used to assemble this stage. You may assume
that the number of previous stages needed will never exceed the number of previous stages defined.

