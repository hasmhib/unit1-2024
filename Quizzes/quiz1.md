# Quiz 001
<img width="977" alt="Screen Shot 2023-09-11 at 22 23 49" src="https://github.com/hasmhib/unit1-2024/assets/142870448/0ff54b81-4352-4ecb-83ef-fccf7b9edc21">

## Code

```py
text = input("Input text: ")
text = text.split()
output = ""
for word in text:
    if len(word) <= 2:
        output += word
    else:
        output += (word[:1] + str(len(word) - 2) + word[-1:])
print(output)
```
