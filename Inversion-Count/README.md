# Sumário

- [Sumário](#sumário)
- [Inversion Count](#inversion-count)
  - [Entrada](#entrada)
  - [Saída](#saída)
  - [Exemplos](#exemplos)
    - [Entrada 1](#entrada-1)
    - [Saída 1](#saída-1)
- [Solução](#solução)

# [Inversion Count](https://vjudge.net/problem/SPOJ-INVCNT)

Let A[0...n - 1] be an array of n distinct positive integers. If i < j and A[i] > A[j] then the pair (i, j) is called an inversion of A. Given n and an array A your task is to find the number of inversions of A.

## Entrada

The first line contains t, the number of testcases followed by a blank space. Each of the t tests start with a number n (n <= 200000). Then n + 1 lines follow. In the ith line a number A[i - 1] is given (A[i - 1] <= 10^7). The (n + 1)th line is a blank space.

## Saída

For every test output one line giving the number of inversions of A.

## Exemplos

### Entrada 1
```
2

3
3
1
2

5
2
3
8
6
1
```

### Saída 1
```
2
5
```

# [Solução](./solution.cpp)

TODO
