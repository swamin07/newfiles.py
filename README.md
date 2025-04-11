# newfiles.py
def factorial(n):
    result = 1
    for i in range(2, n + 1):
        result *= i
    return result

# Calling the function with a sample number
result = factorial(5)
print("Factorial is:", result)
