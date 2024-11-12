Here is the problem statement in English:

---

**Problem:**
Given an array of integers and a positive integer \( k \), determine the number of \((i, j)\) pairs where \( i < j \) and \( ar[i] + ar[j] \) is divisible by \( k \).

**Example**
If:
\( ar = [1, 2, 3, 4, 5, 6] \)
and
\( k = 5 \)

There are three pairs that meet the criteria: \((1, 4)\), \((2, 3)\), and \((4, 6)\).

---

**Function Description**
Complete the `divisibleSumPairs` function in the editor below.

`divisibleSumPairs` has the following parameters:

- `int n`: the length of the array `ar`
- `int ar[n]`: an array of integers
- `int k`: the integer divisor

**Returns**

- `int`: the number of pairs

**Input Format**
The first line contains two space-separated integers, \( n \) and \( k \).  
The second line contains \( n \) space-separated integers, each a value of \( ar[i] \).

**Constraints**

- \( 2 \< n \< 100 \)
- \( 1 \< k \< 100 \)
- \( 1 \< ar[i] \< 100 \)

**Sample Input**

```plaintext
6 3
1 3 2 6 1 2
```

**Sample Output**

```plaintext
5
```

**Explanation**
Here are the 5 valid pairs when \( k = 3 \):

- \( (0, 2) \rightarrow ar[0] + ar[2] = 1 + 2 = 3 \)
- \( (0, 5) \rightarrow ar[0] + ar[5] = 1 + 2 = 3 \)
- \( (1, 3) \rightarrow ar[1] + ar[3] = 3 + 6 = 9 \)
- \( (2, 4) \rightarrow ar[2] + ar[4] = 2 + 1 = 3 \)
- \( (4, 5) \rightarrow ar[4] + ar[5] = 1 + 2 = 3 \)