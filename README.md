﻿# How to code in this programing language

## How it works

### This programing language uses an array to store the vars like this:

    0, 0, 0, 0, 0,...

### And how you use them is with an arrow that starts at position 0:

    0, 0, 0, 0, 0,...
    /\
    ||

### The arrow has a var in it to procces info:

```
0, 0, 0, 0, 0,...
/\
||
0
```

## Arrow movement:
`>` moves the arrow one to the right and `<` moves the arrow one to the left
Or you can use `g` like this:
`g0011` (go to var array pos 11)

## Set vars:
use `s` to set the arrow var like this:
`s0000001234` (set arrow var to 1234)
and like this:
`s-0000000123` (set arrow var to -123)
and to move it to the array use v
but to do the opesite use t.

## Printing:
use nW to print the number from the array at the position of the arrow
use cW to print letters and characters:
```
id 0: 0
id 1: 1
id 2: 2
id 3: 3
id 4: 4
id 5: 5
id 6: 6
id 7: 7
id 8: 8
id 9: 9
id 10: a
id 11: b
id 12: c
id 13: d
id 14: e
id 15: f
id 16: g
id 17: h
id 18: i
id 19: j
id 20: k
id 21: l
id 22: m
id 23: n
id 24: o
id 25: p
id 26: q
id 27: r
id 28: s
id 29: t
id 30: u
id 31: v
id 32: w
id 33: x
id 34: y
id 35: z
id 36: A
id 37: B
id 38: C
id 39: D
id 40: E
id 41: F
id 42: G
id 43: H
id 44: I
id 45: J
id 46: K
id 47: L
id 48: M
id 49: N
id 50: O
id 51: P
id 52: Q
id 53: R
id 54: S
id 55: T
id 56: U
id 57: V
id 58: W
id 59: X
id 60: Y
id 61: Z
id 62: !
id 63: @
id 64: #
id 65: $
id 66: %
id 67: ^
id 68: &
id 69: *
id 70: (
id 71: )
id 72: -
id 73: _
id 74: =
id 75: +
id 76: ;
id 77: :
id 78: '
id 79: ,
id 80: <
id 81: .
id 82: >
id 83: /
id 84: ?
id 85: [
id 86: {
id 87: ]
id 88: }
id 89: "
id 90: \
id 91: |
id 92: `
id 93: ~
id 94:  
```

use `e` to enter

## Math:

`+` set var += array content at current position

`-` set var -= array content at current position

`*` set var *= array content at current position

`:` set var /= array content at current position

`^` set var ^= array content at current position

use ` | ` to: |arrow var|

`%` set var %= array content at current position

use ` cR ` to: get the square root of arrow var

use ` r ` to: get a random number up to array var



## If:
start an if with `i/` and then `=` or `!` or `>` or `<` then the code in the if the to end the if use /i


## Loops:

start a forever loop with `f/` and end it with `/f`

start a while loop with `w/` and end it with `/w` and the first var pos like this: `0000` and then the secend var pos like this: `0000` then the statement like this: `=` or `!` or `>` or `<`

start a for loop with `lT/` (the for max cycle is the arrow var) and end it with `/lT`

start till loop with `T/` and end it with `/T` but to stop it use `eT`



Delay:
delay with `d` in milasecends from arrow var


Complex:
use `j` to move pos in code like this: `j` (reads the var array pos var and goes to that pos in the code)