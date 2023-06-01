# Exercise 1
| i \ j | 1    | 2    | 3    | 4    |
| :---: | :--: | :--: | :--: | :--: |
| 1     | A    | AB   | SAB  |      |
| 2     |      | B    | A    | SA   |
| 3     |      |      | B    | AB   |
| 4     |      |      |      | A    |

# Exercise 2
- Intersection: There is are deciders $A$ and $B$ running in time $O(n^a)$ and $O(n^b)$ respectively.

    ```
    M = "on input w:
        1. Run A on w
        2. Run B on w
        3. if both A and B accepted then accept else reject
    "
    ```

    $M$ runs in time $O(n^a) + O(n^b) + O(1) = O(n^{max(a,b)})$

- Complement: These is a decider $M$ running in time $O(n^k)$.

    ```
    M' = "on input w:
        1. Run M on w
        2. if M accepted then reject else accapt
    "
    ```

    $M'$ runs in time $O(n^k) + O(1) = O(n^k)$

- Concatenation: There is are deciders $A$ and $B$ running in time $O(n^a)$ and $O(n^b)$ respectively.

    ```
    M = "on input w:
        1. i = 0
        2. copy first i of w to tape-2
        3. copy remainder to tape-3
        4. simulate A on tape-2
        5. simulate B on tape-3
        6. if A ond B accepted then accept
        7. clear tape-2
        8. clear tape-3

        2. partition
    "
    ```

# Exercise 3

