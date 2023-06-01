# Exercise 1
1. False
2. False
3. True
4. False

# Exercise 2
1. True, $3n^2 + 2n + 7 \leq 3n^2 + 2n^2 +7n^2 = 12n^2$, for $n >= 1$, thus $n_0 = 1$ and $c = 12$
2. False
3. True, $3^n = 2^{log_2(3) \cdot n} \leq 2^{c \cdot n}$, thus $c = log_2(3)$ and $n_0 = 0$
4. True, $\frac{n^2}{n^3} = \frac{1}{n}$, $\lim_{n \to \infty}\frac{1}{n} = 0$

# Exercise 3
$(n^3)^2 = n^6 = O(n^6)$

# Exercise 4
1. True
2. False
3. True
4. True
5. False

# Exercise 5
$\{ \langle D \rangle | D\ is\ a\ DFA\ accepting\ all\ w \in \Sigma^* \}$

```
"on input <D>:
    1. if D does not encode a DFA then reject
    2. perform BFS on initial node
    3. if reject state is reachable then reject else accept
"
```
