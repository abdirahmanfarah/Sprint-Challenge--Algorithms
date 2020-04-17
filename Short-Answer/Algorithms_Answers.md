#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) It's o(n) because there's only one while loop that is running thus n is
going up in a linear fashion.

b)It's o(n^2) because there are two iterators nested within each other.

c) o(n) because n goes up linearly in the recursive function.

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

<!-- N story building and plenty of eggs -->
<!-- Broken egg if n is equal to or higher than floor f -->
<!-- Determine the value of f -->
<!-- Goal = smallest number of dropped + broken eggs -->

<!-- Figure out the value of n-story building -->
<!-- I know that floor f is equal to 6 because f is the 6th number from a which is 0 -->
<!-- So my strategy would be to see n is greater than 6 -->
<!-- if it is, don't drop the egg -->
<!-- if it isn't greater than 6, drop the egg -->
<!-- Alternatively what if f is not the sixth number of from a -->
<!-- f would be 0, so if n is smaller than 0, drop the egg -->
<!-- if f is larger than 0, don't drop the egg -->
<!-- The runtime complexity of this would be o(1) because we are only determing if n is greater than, equal to, or less than f at which point we drop the egg -->
