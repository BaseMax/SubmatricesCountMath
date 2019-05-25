# Submatrices Count Math

Research: The submatrices character count problem: an efficient solution using separable values.

## Article / Abstract

The subsequence character count problem has as its input an array S = S[1], ... , S[n] of symbols over alphabet A and a natural number m.

Its output is: for every i, i = 1, ... , n − m + 1, the number of different
alphabet symbols occurring in the subsequence S[i], S[i + 1], ... , S[i + m − 1].

The subsequence character count problem is a natural problem that has many uses. It can be solved in linear time for finite alphabets and in time O(n log m) for infinite alphabets.

When the character count problem is generalized to two dimensions it becomes the submatrix character count problem. Its input is an n × n matrix T over alphabet A and a natural number m. Its output is: for every i,j, i,j = 1, ... , n − m + 1, the number of different alphabet symbols occurring in the submatrix T [i + k,j + ], k = 0, ... , m − 1;  = 0, ... , m − 1. The straightforward one-dimensional solution slides a window along the text adding an element and deleting an element at every
step.

The problem with two dimensions is that at every move of the window there are m elements added and
m deleted.

We present an alternate one-dimensional solution that generalizes to two dimensions.

We achieve a O(n2) time solution to the submatrix character count problem over a finite alphabet and a O(n2 log m) solution over an infinite alphabet.


## Result, Research :

For see all of the results, click [here](result.txt) to open the result file.

```
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 1
R = 1111111
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 2
R = 111111
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 3
R = 11111
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 4
R = 1111
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 5
R = 111
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 6
R = 11
RD = 1
--------------
INPUT = AAAAAAA
INPUT = AAAAAAA
N = 7
M = 7
R = 1
RD = 1
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 1
R = 1111111
RD = 1
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 2
R = 111112
RD = 12
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 3
R = 11112
RD = 12
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 4
R = 1112
RD = 12
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 5
R = 112
RD = 12
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 6
R = 12
RD = 12
--------------
INPUT = AAAAAAB
INPUT = AAAAAAB
N = 7
M = 7
R = 2
RD = 2
--------------
INPUT = AAAAAAC
INPUT = AAAAAAC
N = 7
M = 1
R = 1111111
RD = 1
--------------
```

For see all of the results, click [here](result.txt) to open the result file.

