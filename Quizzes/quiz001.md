# Quiz 001
<img width="max" alt="Screen Shot 2023-09-11 at 22 23 49" src="https://github.com/hasmhib/unit1-2024/assets/142870448/0ff54b81-4352-4ecb-83ef-fccf7b9edc21">

## Code

```py
words = input("Input text: ")
words = words.split()
abbreviated_text = []

for word in words:
    if len(word) <= 2:
        abbreviated_text.append(word)
    else:
        abbreviated_text.append(word[0] + str(len(word) - 2) + word[-1])
```

## Proof of work
<img width="646" alt="Screen Shot 2023-09-12 at 0 50 22" src="https://github.com/hasmhib/unit1-2024/assets/142870448/fb7ccfe9-8f3c-403b-95e3-cf67638e9f13">
