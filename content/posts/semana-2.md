+++
title = "Challenge 2"
date = "2023-10-30T13:41:16-04:00"
cover = "Problemas de la semana 2"
tags = ["", ""]
keywords = ["", ""]
description = "Fizz Buzz -- Evil & Odious Numbers -- Anadrome"
readingTime = false
color = "orange" #color from the theme settings
draft = false
+++

# Problema 1: [Fizz Buzz](https://code.golf/fizz-buzz) *(Easy)*
### Task
Print the numbers from `1` to `100` inclusive, each on their own line.
If, however, the number is a multiple of three then print `Fizz` instead, and if the number is a multiple of five then print `Buzz`.
If multiple conditions hold true then all replacements should be printed, for example `15` should print `FizzBuzz`.

### Output
The first 30 lines are the following:
```txt
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
Fizz
22
23
Fizz
Buzz
26
Fizz
28
29
FizzBuzz
```

# Problema 2: [Evil/Odious Numbers](https://code.golf/odious-numbers-long) *(Medium)*
Un numero `evil` es un entero positivo que tiene una cantidad par de unos en su
representacion binaria.
Ademas, un numero `odious` tiene una cantidad impar de unos en su representacion
binaria.

### Output
Imprime todos los numeros `evil` del [1, 50] y todos los numeros `odious` del
[1, 1000].

*BONO*: codifica la solucion utilizando la menor cantidad de caracteres
posibles.

# Problema 3: [Anadrome](https://rosettacode.org/wiki/Anadromes) *(Hard)*
An anadrome is similar to a palindrome except, rather than spelling the same word or phrase when reversed, it spells a different word or phrase.
An anadrome is a special case of an anagram.

For instance, regal and lager are anadromes.

### Output
Using the `words.txt` file from `https://github.com/dwyl/english-words`, find and display all of the anadrome pairs with more than 6 characters.
Each word pair should only show up one time in the list.
