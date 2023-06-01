# Exercise 1
No, since $ATM \subseteq \{w | w \in \Sigma^*\}$.

# Exercise 2
### 2.1
$\{\langle R \rangle | R\ is\ a\ regular\ expression\ accepting\ 11w0 \in \Sigma^*\}$

### 2.2
```
"on input r:
    1. check that r is an encoding of a regular expression, if not reject
    2. create the DFA G for r
    3. G has a initial-node-0->u-1-->v, if not reject
    4. G has a s-0->accapt, if not reject
    5. G has a path v->*s, if not reject
    6. accapt
"
```

# Exercise 3
### Union
Since this is the union between two decidable languages $L_1,L_2$ there must exist deciders $M_1, M_2$.

```
"on input w:
    1. run M1 on x, if M1 accepts then accept
    2. run M2 on x, if M2 accapts then accept
    3. reject
"
```

### Concatenation
```
"on input x:
    1. for every partition (u,v) = ("", x) to (x, "")
        2. run M1 on u
        3. run M2 un v
        4. if M1 and M2 accepted then accept
    5. reject
"
```

### Kleene star
```
"on input x:
    1. if x is the empty string then accept
    2. for all possible sequences w1..wn = x
        3. run M on w1 to wn
        4. if M accapted in all cases then accapt
    5. reject
"
```

# Exercise 4
### Intersection
```
"on input x:
    1. copy x to tape-2
    2. on tape-1 run M1 on x
    3. on tape-2 run M2 on x
    4. if M1 and M2 accept then accept
"
```

# Exercise 5
**Proof 1:** since M is a recognizer it may loop, in this case M' will loop as well, but it should accept.

**Proof 2:** You can not check if a TM loops

# Exercise 6
```
"on input x:
    1. x encodes a CFG, if not reject
    2. for all rules r -> 1 push r to a stack s
    3. if s is empty then reject
    4. pop r from s
    5. push r to stack s'
    6. for all rules r' -> r push r'
    7. if r' = S then accept
    8. if r' is not in s' then push r' to s
    9. go to step 3
```
