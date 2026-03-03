# C Wordle: Design Document

* author: *Kaley Yew*



## introduction

In this program, I will implement a fun game to amuse and amaze my friends and loved ones.

TODO(you): I'll write a code that is wordle!

## function 1: score\_guess

go through and compare guess and secret. if the letter is in the word and right spot replace the place in result with g. if it is in the word but not the right spot replace the spot in result with y and if it not in the word replace with x. if result is five gs then result return true otherwise result false.

## function 2: valid\_guess

first check that the word is of length five. then compare the guess and vocabulary through linear search. if it is a valid word (in vocabulary) then return true. otherwise return false.

## function 3: load\_vocabulary

allocate memory for words. open(fopen) and read each lines of the vocabulary file. copy each word(strdup) into memory making an array. make a count of how many word is in it. return the list and count.

## function 4: free\_vocabulary

go through the vocabulary array with the count. free each word as it goes through the for loop. free the memory of the list.

