# FIBONACCI-NUMBERS
def fibonacci(n):
    fib_sequence = [0, 1]
    while len(fib_sequence) < n:
        fib_sequence.append(fib_sequence[-1] + fib_sequence[-2])
    return fib_sequence[:n]

# Example usage:
n = 15  # Change this value to generate more or fewer Fibonacci numbers
fib_numbers = fibonacci(n)
print(f"The first {n} Fibonacci numbers are: {fib_numbers}")
