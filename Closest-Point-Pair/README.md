# Sumário

- [Sumário](#sumário)
- [Closest Point Pair](#closest-point-pair)
  - [Entrada](#entrada)
  - [Saída](#saída)
  - [Exemplos](#exemplos)
    - [Entrada 1](#entrada-1)
    - [Saída 1](#saída-1)
    - [Entrada 2](#entrada-2)
    - [Saída 2](#saída-2)
- [Solução](#solução)

# [Closest Point Pair](https://vjudge.net/problem/SPOJ-CLOPPAIR)

You are given N points on a plane and your task is to find a pair of points with the smallest Euclidean distance between them.

All points will be unique and there is only one pair with the smallest distance.

## Entrada

First line of input will contain N (2<=N<=50000) and then N lines follow each line contains two integers giving the X and Y coordinate of the point. Absolute value of X,Y will be at most 10^6.

## Saída

Output 3 numbers a b c, where a, b (a < b) are the indexes (0 based) of the point pair in the input and c is the distance between them. Round c to 6 decimal digits.

See samples for more clarification.

## Exemplos

### Entrada 1
```
5
0 0
0 1
100 45
2 3
9 9
```

### Saída 1
```
0 1 1.000000
```

### Entrada 2
```
5
0 0
-4 1
-7 -2
4 5
1 1
```

### Saída 2
```
0 4 1.414214
```

# [Solução](./solution.cpp)

TODO
