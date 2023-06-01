# Exercise 1
1. yes, the tape alphabet $\Gamma = \Sigma \cup \{\sqcup\}$.
2. no.
3. yes, when going left on the leftmost tape cell.
4. no, the state set must contain $q_{reject}$ and $q_{accept}$.

# Exercise 2
1. Wrong, a language does not halt a TM does.
2. Correct.
3. Wrong, same as 1.
4. Wrong, a TM is not a member a language an encoding may be, but the statement here is nonsense.
5. Correct.
6. Wrong, there just needs to be a singular TM which halts in $q_{accept}$ iff $x \in L$.

# Exercise 3
A language $L \subseteq \Sigma^*$ is decidable iff there exists a decider M such that M recognizes the language $L$.

# Exercise 4
1. A TM is deterministic, it may only be in a singular state at any given time.
2. Yes.

# Exercise 5
$q_0 a a b b a a$

$\sqcup q_1 a b b a a$

$\sqcup a q_1 b b a a$

$\sqcup a x q_2 b a a$

$\sqcup a x b q_2 a a$

$\sqcup a x b x q_3 a$

$\sqcup a x b q_4 x a$

$\sqcup a x q_4 b x a$

$\sqcup a q_4 x b x a$

$\sqcup q_4 a x b x a$

$q_4 \sqcup a x b x a$

$\sqcup q_5 a x b x a$

$\sqcup x q_1 x b x a$

$\sqcup x x q_1 b x a$

$\sqcup x x x q_2 x a$

$\sqcup x x x x q_2 a$

$\sqcup x x x x x q_3 \sqcup$

$\sqcup x x x x q_6 x$

$\sqcup x x x q_6 x x$

$\sqcup x x q_6 x x x$

$\sqcup x q_6 x x x x$

$\sqcup q_6 x x x x x$

$q_6 \sqcup x x x x x$

$q_{accept} \sqcup x x x x x$

