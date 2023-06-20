# Sumário

- [Sumário](#sumário)
- [Golf Bot](#golf-bot)
  - [Entrada](#entrada)
  - [Restrições](#restrições)
  - [Saída](#saída)
  - [Exemplos](#exemplos)
    - [Entrada 1](#entrada-1)
    - [Saída 1](#saída-1)
- [Solução](#solução)

# [Golf Bot](https://vjudge.net/problem/UVA-12879)

Do you like golf? I hate it. I hate golf so much that I
decided to build the ultimate golf robot, a robot that
will never miss a shot. I simply place it over the ball,
choose the right direction and distance and, awlessly,
it will strike the ball across the air and into the hole.
Golf will never be played again.
Unfortunately, it doesn't work as planned. So, here
I am, standing in the green and preparing my rst
strike when I realize that the distance-selector knob
built-in doesn't have all the distance options! Not ev-
erything is lost, as I have 2 shots.
Given my current robot, how many holes will I be
able to complete in 2 strokes or less? The ball must be
always on the right line between the tee and the hole.
It isn't allowed to overstep it and come back.

## Entrada

The input le contains several test cases, each of them
as described below.
The rst line has one integer: N , the number of
different distances the Golf Bot can shoot. Each of
the following N lines has one integer, ki, the distance
marked in position i of the knob.
Next line has one integer: M , the number of holes in this course. Each of the following M lines has
one integer, dj , the distance from Golf Bot to hole j.

## Restrições

1 ≤ N, M ≤ 200 000
1 ≤ ki, dj ≤ 200 000

## Saída

For each test case, you should output a single integer, the number of holes Golf Bot will be able to
complete. Golf Bot cannot shoot over a hole on purpose and then shoot backwards.
Sample Output Explanation
Golf Bot can shoot 3 different distances (1, 3 and 5) and there are 6 holes in this course at distances
2, 4, 5, 7, 8 and 9. Golf Bot will be able to put the ball in 4 of these:
• The 1st hole, at distance 2, can be reached by striking two times a distance of 1.
• The 2nd hole, at distance 4, can be reached by striking with strength 3 and then strength 1 (or
vice-versa).
• The 3rd hole can be reached with just one stroke of strength 5.
• The 5th hole can be reached with two strikes of strengths 3 and 5.
Holes 4 and 6 can never be reached.

## Exemplos

### Entrada 1
```
3
1
3
5
6
2
4
5
7
8
9
```

### Saída 1
```
4
```

# [Solução](./solution.cpp)

TODO
