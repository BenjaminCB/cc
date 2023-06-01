# Exercise 1
$h(w) = g(f(w))$, there must exist TMs for $f$ and $g$

```
"on input w:
    1. x = run F on w
    2. y = run G on x
    3. output y
"
```

# Exercise 2
# Exercise 3
$ Exercise 4
In order to prove the claim, it is enough to show that $\overline{A_{TM}} \leq_m REGULAR_{TM}$ and $\overline{A_{TM}} \leq_m \overline{REGULAR_{TM}}$

- We prove that $\overline{A_{TM}} \leq_m REGULAR_{TM}$ be show that $A_{TM} \leq_m \overline{REGULAR_{TM}}$

    ```
    M1 =
        "on input <M,w> where M is a TM:
            1. using M and w construct M'
                "on input x:
                    1.
                "
            2. output <M'>
        "
    ```

# Extra Exercise 1
For a language to be decidable it needs to be both recognizable and co-recognizable. This is because we need to be able to determine both the positive and negative cases for whether a word w is in a language L.

# Extra Exercise 2
1.
