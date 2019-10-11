#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime is `O(n)` after is simplified from `O(1 + n)`. The while loop will break after `a + n * n` is added `n` times to `a`.


b) The runtime is `O(n * sqrt(n))`. The first loop will iterate over `n`, and the second one is adding `j**2` until `n` is reached, so that is `sqrt(n)` times.


c) The runtime is `O(n)`. It's a recursive function that is going to be executed `n` times until `bunnies == 0`, and every time the function is returned with `bunnies - 1`, so it will take `n` times to arrive to the base case of the recursion.

## Exercise II
