# Sumário

- [Sumário](#sumário)
- [Power of matrix](#power-of-matrix)
  - [Entrada](#entrada)
  - [Saída](#saída)
  - [Exemplos](#exemplos)
    - [Entrada 1](#entrada-1)
    - [Saída 1](#saída-1)
- [Solução](#solução)

# [Power of matrix](https://vjudge.net/problem/SPOJ-MPOW)

You will be given a square matrix M and a positive integer power N. You will have to compute M raised to the power N. (that is, M multiplied with itself N times.)

## Entrada

First line of input is **T** ( number of test-cases) First line of each test-case contains two integer M , N where M is size of square matrix that we have to exponent and N is the power to which we have to exponent
Next M lines describe the input matrix. Each line contains exactly M elements corresponding to each array

## Saída

Output M line corresponding to each row of resultant matrix Each line must have M integers where jth element of ith line is jth element of resultant matrix taken modulo with **1000000007** (10^9+7).

Simply , you have to print the resultant square matrix.

## Exemplos

### Entrada 1
```
2
2 3
1 0
1 1
3 3
1 0 4
1 2 2
0 4 4
```

### Saída 1
```
1 0
3 1
17 112 116
15 88 100
28 144 160
```

# [Solução](./solution.cpp)

TODO
