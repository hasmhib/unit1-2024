# Quiz 005

<img width="max" alt="Screen Shot 2023-09-11 at 23 03 16" src="https://github.com/hasmhib/unit1-2024/assets/142870448/ab39034b-c397-45d6-b598-f8ddf3dc7abf">

## Code
```py
def sum_letters(text:str)->int:
    alphabet= "abcdefghijklmnopqrstuvwxyz"
    sum = 0
    for let in text.lower():
        index =-1
        for i in range(len(alphabet)):
            if let == alphabet[i]:
                index = i + 1
        sum += index
    return sum
```

## Proof of work

```py
case1 = sum_letters(text="math")
print (case1)

case2 = sum_letters(text="maTH")
print (case2)

case3 = sum_letters(text="Hello world")
print (case3)
```

<img width="max" alt="Screen Shot 2023-09-11 at 23 07 40" src="https://github.com/hasmhib/unit1-2024/assets/142870448/489a6540-a27e-4dfe-bf52-ac2d44e2e1c2">

## The Flowchart

![IMG_5718](https://github.com/hasmhib/unit1-2024/assets/142870448/35297ffb-2ec5-40b9-b529-deea98cd1289)

