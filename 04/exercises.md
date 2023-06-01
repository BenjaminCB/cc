# Exercise 1
Both claims are wrong, since $\empty \subseteq A_{TM} \subseteq \Sigma^*$.

# Exercise 2
### $L_1$
```
"on input <A,B>:
    1. compute the DFA AB equal to the intersection of A and B
    2. if AB contains an accept state then reject else accept
"
```

### $L_2$
```
"on input <M>:
    1. count the states of <M> if it more than 5 accept else reject
"
```

### $L_3$
```
"on input <M,w>:
    1. copy w to tape-2
    2. for i = 1 to 999
        3. perform a single computation step of M on tape-2
        4. if M accepted then accepted
    5. reject
"
```
### $L_4$
This is not decidable as there will always be another computation step.

### $L_5$
This is $HALT_{TM}$ and is undeciable.
