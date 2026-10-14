# Profile: Athalla Daffaa Wardhana

- **NetID:** awad93
- **Major:** Computer Science
- **Question that I chose from the memoization exercise:** Program for Fibonacci numbers
- **Link to the question article:** [Nth Fibonacci Number](https://www.geeksforgeeks.org/dsa/program-for-nth-fibonacci-number/)
- **My solution:**
```c
int nthFibonacci(int n) {
    
    if (n == 0) {
        return 0;
    }
    else if (n == 1) {
        return 1;
    }
    else {
        return nthFibonacci(n - 1) + nthFibonacci(n - 2);
    }
    
}
```

