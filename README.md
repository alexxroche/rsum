## A simple game where you have to recursively sum the digits ##

https://alexxroche.github.io/rsum 

Each time that you correctly sum them in time the next number, (may) have an additional digit.

Progressive mode (the default) adds a new digit to the existing number.
Random (enough, this isn't crypto) creates a new number, (much harder so bigger scores!)

e.g.  56 => 2  [5+6 = 11; 1+1 = 2]
    Progressive
      563 => 5 [ 6+3 = 9; 5+9 = 14; 4+1 = 5] (or you can just do 3+2 = 5 where 2 comes from the first answer).

    Random
      822 => 3 [ 8+2 = 10; 1+2 = 3 | 10+2 = 12; 1+2 = 3 ]

100% Javascript. Keeps a record of your best scores. Has guest mode so that others can play. Has "vs mode" so that one can use the keypad and another the number keys in a head-to-head race.      


### Dependencies ###

ECMAscript
https://lhorie.github.io/mithril-blog/ https://mithril.js.org/

### Number theory ###
This comes from the area of mathematics known as Digital Roots, and can be useful for predicting divisibility of a number.
