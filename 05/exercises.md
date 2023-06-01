# Exercise 1
1. False
2. False
3. True

# Exercise 2
# Exercise 3
$\{\langle M \rangle | M\ accepts\ 0010\}$

Assume there is a TM N which is a decider for $L_{0010}$
```
"on input <M, w>:
    1. costruct M'
        "on input x:
            1. if x == 0010 then M' rejects
            2. if x != 0010 then simulate M on w
                if M
        "
"
```

# Exercise 4
$\{\langle M \rangle | M\ is\ TM\ such\ that\ L(M) = \Sigma^*\}$

There exists a decider R for $TOTAL_{TM}$.
```
"on input <M,w>:
    1. using M and w construct TM M'
        "on input x:
            1. if x != w accept
            2. if x == w then run M on w
                if M accapted
                then accept
                else reject
        "
    2. run R on <M'>
    3. if R accepted then accept else reject
"
```


