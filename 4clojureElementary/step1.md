If you already done the first step I made you already have all ready for run the command bellow on your terminal and start lein.

To run Clojure you can just type `lein repl`{{execute}} on a Terminal.

The first problem show you the boolean on clojure are in this [link](https://www.4clojure.com/problem/1)

there are a few answers for (= __ true) some of them are

`(= true true)`{{execute}}
 
 or
 
`(= (not false) true)`{{execute}}

or 

`(= (= 3 3) true)`{{execute}}


any of these answers should give you the correct answer

**HOW CLOJURE PROCESS THIS** 

First clojure will solve the operand '=' after this he will look for 
the next to parameters (true) | (not false) | (= 3 3) and will
check if this is equals to the second (true) this is called [Polish notation](https://en.wikipedia.org/wiki/Polish_notation)
in this link you will find more details about that