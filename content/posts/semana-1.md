+++
title = "Challenge 1"
date = "2023-10-25T13:41:16-04:00"
author = ""
authorTwitter = "" #do not include @
cover = "Problemas de la semana 1"
tags = ["", ""]
keywords = ["", ""]
description = "Suma -- Population Count -- Checksum"
showFullContent = false
readingTime = false
hideComments = false
color = "blue" #color from the theme settings
draft = false
+++

# Problema 1: Suma *(Easy)*
Tiene tres enteros `a`, `b` y `c`.
Determina si uno de ellos es la suma de los otros dos.

### Example input
La primera linea contiene un entera `t` tal que `1 <= t <= 9261`, este es la
cantidad de casos.
Cada caso consiste de tres numeros `a`, `b` y `c` tal que `0 <= a, b, c <= 20`.
No tienes que hacer "input validation".

```
7
1 4 3
2 5 8
9 11 20
0 0 0
20 20 20
4 12 3
15 7 8
```

### Example output
Para cada caso, imprime `YES` si uno de los numeros es la suma de los otros dos.
Al contrario, imprime `NO`.

No importan las mayusculas, por lo tanto puedes imprimir `yEs`, `yeS` o `Yes` 
tambien.
```
YES
NO
YES
YES
NO
NO
YES
```

# Problema 2: [Population count](https://rosettacode.org/wiki/Population_count) *(Medium)*
The population count is the number of 1s (ones) in the binary representation of
a non-negative integer.

Write a function (or routine) to return the population count of a non-negative
integer.
 -  display the pop count of the 1st thirty powers of 3 (3, 9, 27, 81, 243,
 ∙∙∙ 205891132094649).


# Problema 3: [Checksum](https://adventofcode.com/2018/day/2) *(Hard)*
Late at night, you sneak to the warehouse and use your fancy wrist device to
quickly scan every box and produce a list of the likely candidates
(your puzzle input).

To make sure you didn't miss any, you scan the likely candidate boxes again,
counting the number that have an ID containing exactly two of any letter and
then separately counting those with exactly three of any letter.
You can multiply those two counts together to get a rudimentary
[checksum](https://en.wikipedia.org/wiki/Checksum) and compare it to what your
device predicts.

### Input
For example, if you see the following box IDs:

- `abcdef` contains no letters that appear exactly two or three times.
- `bababc` contains two a and three b, so it counts for both.
- `abbcde` contains two b, but no letter appears exactly three times.
- `abcccd` contains three c, but no letter appears exactly two times.
- `aabcdd` contains two a and two d, but it only counts once.
- `abcdee` contains two e.
- `ababab` contains three a and three b, but it only counts once.

### Output
Of these box IDs, four of them contain a letter which appears exactly twice,
and three of them contain a letter which appears exactly three times.
Multiplying these together produces a checksum of 4 * 3 = 12.
```
12
```
