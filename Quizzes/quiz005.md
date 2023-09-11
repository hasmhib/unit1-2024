# Quiz 005

<img width="max" alt="Screen Shot 2023-09-11 at 23 03 16" src="https://github.com/hasmhib/unit1-2024/assets/142870448/ab39034b-c397-45d6-b598-f8ddf3dc7abf">

## Code for SL
```py
# Function to calculate the sum of letter positions in the English alphabet (SL: Standard Level)
def sum_letters_sl(text: str) -> int:
    # Define the English alphabet
    alphabet = "abcdefghijklmnopqrstuvwxyz"

    # Initialize the sum variable to 0
    sum = 0

    # Iterate through each letter in the input text, converting it to lowercase
    for let in text.lower():
        index = -1  # Initialize the index variable to -1

        # Iterate through the alphabet to find the index of the letter
        for i in range(len(alphabet)):
            if let == alphabet[i]:
                index = i + 1  # Set the index to the position of the letter in the alphabet
        sum += index  # Add the index to the sum

    # Create the output string with the input text and the sum for SL
    output = f"'{text}' for SL: {sum}"

    # Return the output string
    return output
```

## Proof of work for SL
```
case1 = sum_letters_sl(text="math")
print(case1)

case2 = sum_letters_sl(text="maTH")
print(case2)

case3 = sum_letters_sl(text="Hello world")
print(case3)

case4 = sum_letters_sl(text="Computer SCIENCE")
print(case4)
```

<img width="max" alt="Screen Shot 2023-09-12 at 2 00 23" src="https://github.com/hasmhib/unit1-2024/assets/142870448/dbf1d894-ba40-4ec3-a241-ea4133e1d800">


## Code for HL
```py
# Function to calculate the sum of letter positions in the English alphabet (HL: Higher Level)
def sum_letters_hl(text: str):
    SumOfCharacters = 0

    # Iterate through each letter in the input text
    for letter in text:
        if letter.islower():
            # For lowercase letters, add the ASCII value minus 64 minus 6 to the sum
            SumOfCharacters += ord(letter) - 64 - 6
        if letter.isupper():
            # For uppercase letters, add the ASCII value minus 64 to the sum
            SumOfCharacters += ord(letter) - 64

    # Create the output string with the input text and the sum for HL
    output = f"'{text}' for HL: {SumOfCharacters}"

    # Return the output string
    return output
```

## Proof of work for HL
```
case1_hl = sum_letters_hl(text="math")
print(case1_hl)

case2_hl = sum_letters_hl(text="maTH")
print(case2_hl)

case3_hl = sum_letters_hl(text="Hello world")
print(case3_hl)
```

<img width="max" alt="Screen Shot 2023-09-12 at 1 59 30" src="https://github.com/hasmhib/unit1-2024/assets/142870448/fbea1c98-017f-43fb-a271-ff211114fc0f">


## The Flowchart

![IMG_5718](https://github.com/hasmhib/unit1-2024/assets/142870448/35297ffb-2ec5-40b9-b529-deea98cd1289)

