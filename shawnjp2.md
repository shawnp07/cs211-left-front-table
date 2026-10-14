# Profile: Shawn Plackiyil

- **NetID:** shawnjp2
- **Major:** Computer Science
- **Question that I chose from the memoization exercise:** Ways to Reach the n'th Stair
- **Link to the question article:** https://www.geeksforgeeks.org/problems/count-ways-to-reach-the-nth-stair-1587115620/1
- **My solution:**

```

int countWays(int n) {
    if(n == 1) return 1;
    return n / 2 + countWays(n - 1);
}

int main() {
    printf("%d", countWays(40));
    return 0;
}

```