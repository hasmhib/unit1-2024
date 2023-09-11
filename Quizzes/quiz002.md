# Quiz 002
<img width="max" alt="Screen Shot 2023-09-11 at 22 31 16" src="https://github.com/hasmhib/unit1-2024/assets/142870448/97a28f9d-e79a-41a1-adb3-7ff5ee87023b">

## Code for SL

```py
# Define the input lists A and B
A = [10, 30, 10, 26]
B = [20, 15, 5, -6]

# Initialize the output variable to False
output = False

# Loop through the elements of A and B using their indices
for i in range(len(A)):
    # Check if either A[i] is equal to 20, B[i] is equal to 20, or their sum is equal to 20
    if A[i] == 20 or B[i] == 20 or A[i] + B[i] == 20:
        # If any of the conditions are met, set the output to True
        output = True

# Print the final output
print(output)

```

## Proof of work for SL
<img width="max" alt="Screen Shot 2023-09-12 at 2 12 59" src="https://github.com/hasmhib/unit1-2024/assets/142870448/188eaa8a-d030-45b7-9da5-71d9b42fc3d9">


## Code for HL

```py
# Define the input lists HL
HL = [[10, 30, 10, 26], [20, 15, 5, -6]]

# Initialize the output variable to False
output = False

# Loop through the elements of the first list (HL[0]) and the second list (HL[1]) using their indices
for i in range(len(HL[0])):
    # Check if either the element in the first list (HL[0][i]) is equal to 20,
    # the element in the second list (HL[1][i]) is equal to 20,
    # or their sum is equal to 20
    if HL[0][i] == 20 or HL[1][i] == 20 or HL[0][i] + HL[1][i] == 20:
        # If any of the conditions are met, set the output to True
        output = True

# Print the final output
print(output)
```

## Proof of work for HL
<img width="max" alt="Screen Shot 2023-09-12 at 2 12 10" src="https://github.com/hasmhib/unit1-2024/assets/142870448/be9b2a00-6a93-4897-a4c9-2717e02e0039">
