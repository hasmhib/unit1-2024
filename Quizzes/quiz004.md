# Quiz 004
<img width="max" alt="Screen Shot 2023-09-11 at 22 40 35" src="https://github.com/hasmhib/unit1-2024/assets/142870448/22eba99d-7343-4dbd-8e63-6ad0a5778fe5">

## Code

```py
# Prompt the user for input, expecting an integer
number = int(input("Enter a number: "))

# Create an empty list to store the factors of the number
factor = []

# Initialize a variable to keep track of the sum of factors
sum_of_factors = 0

# Iterate through numbers from 1 to half of the input number
for i in range(1, number // 2 + 1):
    # Check if 'i' is a factor of 'number' (no remainder)
    if number % i == 0:
        # If 'i' is a factor, add it to the 'factor' list
        factor.append(i)

        # Add 'i' to the sum of factors
        sum_of_factors += i

# Check if the sum of factors equals the input number
if sum_of_factors == number:
    print(f"{factor}, True")
else:
    # If the sum of factors is not equal to the input number, print False
    print(f"{factor}, False")

```

## Proof of work
<img width="max" alt="Screen Shot 2023-09-12 at 1 38 58" src="https://github.com/hasmhib/unit1-2024/assets/142870448/ea2131e6-7150-45dd-b4ee-6c1b4fd4d961">

<img width="max" alt="Screen Shot 2023-09-12 at 1 39 23" src="https://github.com/hasmhib/unit1-2024/assets/142870448/b29a463b-2295-4847-a70b-7148b1d0e883">
