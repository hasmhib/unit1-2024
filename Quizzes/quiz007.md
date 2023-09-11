# Quiz 007
<img width="max" alt="Screen Shot 2023-09-12 at 0 28 38" src="https://github.com/hasmhib/unit1-2024/assets/142870448/43ace6a7-a5e6-4b95-a6d7-a7f9226d0b7d">

## Code
```py
# Import the random module to generate random numbers
import random

# Initialize the 'number' variable with a random integer between 1 and 100
number = random.randint(1, 100)

# Initialize the 'attempt' variable to count the number of attempts
attempt = 0

# Use a while loop to keep generating random numbers until 'number' is less than or equal to 15
while number > 15:
    # Generate a new random number between 1 and 100
    number = random.randint(1, 100)
    
    # Increment the 'attempt' count
    attempt += 1

# Print the number of attempts it took to get a number smaller than 15
print(f"It took {attempt} times to get a number that is smaller than 15")

```

## Proof of works
<img width="max" alt="Screen Shot 2023-09-12 at 2 09 48" src="https://github.com/hasmhib/unit1-2024/assets/142870448/db200298-bb1d-47f5-b1c9-8d8fae519e06">
