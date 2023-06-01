# Exercise 1
1. correct
2. incorrect
3. incorrect
4. correct

# Exercise 2
1. $\{ \langle S, M, k \rangle | S = \{s_1, \dots, s_n \}
                               , s_1,\dots,s_n,M,k \in \mathbb{N}
                               , there exe\}$

2.
    ```
    "on input <S, k, M>:
        1. nondeterminstically partition S into S1,...SK
        2. for i = 0 to k if sum of Si > M reject
        3. accept
    "
    ```

3.
    ```
    "on input <S, k, M, Ss>:
        1. Ss is an encoding of a set S1, ..., SK, else reject
        2. if union of S1, ..., SK != S then reject
        3. for i = 0 to k if sum of Si > M then reject
        4. accept
    "
    ```

# Exercise 3
1. not a decider there will always be more computation branches since $\mathbb{N}$ is an infinite set.
2. writing $2^n$ nodes takes exponential time
3.
