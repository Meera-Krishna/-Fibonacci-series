# -Fibonacci-series
def fibonacci(n):
    fib_series = [0, 1]
    
    for i in range(2, n):
        next_number = fib_series[-1] + fib_series[-2]
        fib_series.append(next_number)
    
    return fib_series

# Change the value of 'n' to the number of Fibonacci numbers you want to generate
n = 10
result = fibonacci(n)

print(f"The first {n} numbers in the Fibonacci series are: {result}")
