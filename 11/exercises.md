# Exercise 1
The definition should be: A language $L$ is NP-complete if $L \in NP$ and $\forall L' \in NP. L' \leq_p L$

# Exercise 2
1. Correct, since since $L_1$ and $L_2$ are NP Complete they are both in $NP$ and $\forall L \in NP. L \leq_p L_1 \wedge L \leq_p L_2$
2. Correct, by same reasoning as above
3. Incorrect, To be NP-complete all other languages in NP have to be polynomial time reducible to L, which the statement says nothing about.
4. Correct, since $\leq_p$ is transitive. (wrong)

# Exercise 3
- aaa:
    |  a  |  a  |  a  |
    | :-: | :-: | :-: |
    |  a  |  a  |  a  |

    |  a  |  a  |  a  |
    | :-: | :-: | :-: |
    |  q  |  a  |  a  |

    |  a       |  a  |  a  |
    | :-:      | :-: | :-: |
    | $\sqcup$ |  a  |  a  |

    |  a  |  a  |  a    |
    | :-: | :-: | :-:   |
    |  a  |  a  | $q_r$ |

- #aa:

    |  #  |  a  |  a  |
    | :-: | :-: | :-: |
    |     |     |     |

    |  #  |  a  |  a  |
    | :-: | :-: | :-: |
    |     |     |     |

# Exercise 4

