# Quiz 001
<img width="max" alt="Screen Shot 2023-09-11 at 22 23 49" src="https://github.com/hasmhib/unit1-2024/assets/142870448/0ff54b81-4352-4ecb-83ef-fccf7b9edc21">

## Code

```py
# Prompt the user for input
words = input("Input text: ")

# Split the input text into words
words = words.split()

# Create an empty list to store abbreviated words
abbreviated_text = []

# Iterate through each word in the input text
for word in words:
    # Check if the word has 2 or fewer characters
    if len(word) <= 2:
        # If it does, keep the word as is and append to the list
        abbreviated_text.append(word)
    else:
        # If it has more than 2 characters, abbreviate it by replacing
        # the middle characters with their count and append to the list
        abbreviated_text.append(word[0] + str(len(word) - 2) + word[-1])

# Join the abbreviated words in the list using a space as a separator
result = ' '.join(abbreviated_text)

# Print the resulting abbreviated text
print(result)
```

## Proof of work
<img width="max" alt="Screen Shot 2023-09-12 at 2 10 59" src="https://github.com/hasmhib/unit1-2024/assets/142870448/451e6a9c-d596-45f4-99dd-f073c803d6cd">


