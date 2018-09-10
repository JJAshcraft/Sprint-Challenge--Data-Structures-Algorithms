Add your answers to the Algorithms exercises here.
a. O(n)
b. O(n^3) (last loop is not n time)
c. O(n)
d. My strategy would be to use Divide and Conquer. Go to the midpoint of the building,
drop an egg and if it breaks, assume that anything dropped from higher will also break.

Next, go the midpoint up to the last floor and repeat. If the egg breaks, we are still too high, and need to divide in half again. If it does not break, we need to go up to the next midpoint between this floor and the last floor and repeat, until we figure out which two floors are the line between an egg breaking and not breaking.