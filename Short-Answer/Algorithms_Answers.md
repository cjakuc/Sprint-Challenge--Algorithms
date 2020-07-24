#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
The time complexity of this code is O(n). Although the while loop runs until "a" is greater than n^3, "a" is incremented by n^2 each iteration.

b)
The time complexity of this code is O(n * log n). There are two loops (one within the other), both dependent on the size of "n". The first loop has a run-time complexity of O(n). The second loop has a run-time complexity of O(log n). Because the second loop is within the first, the run-time complexities are multiplied to get O(n * log n)

c)
The time complexity of this code is O(n). For every value of "bunnies" greater than 0, the function will recurse 1 + "bunnies" amount of times.

## Exercise II


<!-- function def (list): -->
    <!-- make pointers for first and last floor -->
    <!-- make boolean for if you found the right floor -->

    <!-- while loop while pointer from first floor is less than or equal to last and found boolean is false -->

        <!-- get the middle floor -->

            <!-- drop an egg -->

            <!-- if it breaks -->
                <!-- make the last floor the value of the current middle -->

            <!-- if it doesn't break -->
                <!-- make the first floor the value of the current middle -->

            <!-- Keep looping until you find the highest floor where the egg doesn't break -->

Run-time complexity is O(log n)