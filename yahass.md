# Profile: Yusuf Hassan

- **NetID:** 671237878
- **Major:** Computer Science
- **Question that I chose from the memoization exercise:** Program for Fibonacci numbers
- **Link to the question article:** [Nth Fibonacci Number](https://www.geeksforgeeks.org/dsa/program-for-nth-fibonacci-number/)
- **My solution:**

\```

int nthFibonacci(int n) {
    
    // base case
    if (n <= 1){
        return n;
    }
    return nthFibonacci(n - 1) + nthFibonacci(n - 2);
}

\```