# The-mysterious-weighing
You have 12 identical-looking balls, and one of them is slightly lighter than the others. You also have a two-pan balance scale that can compare the weight of two sets of balls. You are allowed to perform the weighing operation only three times.

How can you find the lighter ball using the scale only three times?

Solution:
Divide the 12 balls into three groups of four balls each (Group A, Group B, and Group C). Perform the weighings as follows:

Weighing 1: Compare Group A and Group B

If Group A and Group B are balanced, the lighter ball is in Group C.
If Group A is lighter than Group B, then the lighter ball must be one of the four balls in Group A.
If Group A is heavier than Group B, then the lighter ball must be one of the four balls in Group B.
Weighing 2: Take the lighter group (either Group A or Group B from Weighing 1) and divide it into two sets of two balls each (Group X and Group Y). Put one set on each side of the scale.

If Group X and Group Y balance, the lighter ball is one of the remaining two balls in that group.
If Group X is lighter than Group Y, then the lighter ball must be one of the two balls in Group X.
If Group X is heavier than Group Y, then the lighter ball must be one of the two balls in Group Y.
Weighing 3: Take the lighter group (either Group X or Group Y from Weighing 2) and put one ball on each side of the scale.

If they balance, the lighter ball is the one not weighed in Weighing 3.
If one side is lighter, that ball is the lighter ball.
In this way, you can determine the lighter ball using the scale only three times.
