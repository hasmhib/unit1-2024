# Quiz 010
<img width="max" alt="Screen Shot 2023-10-09 at 12 12 43" src="https://github.com/hasmhib/unit1-2024/assets/142870448/c2b89bec-eaa4-4666-b8d2-4ea1f80e0eb0">


## Code
```py
out = ''
days = ['Fr', 'Sa', 'Su', 'Mo','Tu', 'We', 'Th']
count = 0

for d in range (7):
    out += f"{days[d]}".center(8)
out += '\n'

for d in range (1,31):
    out += f"{d:2d}".center(8)
    count += 1
    if count > 6:
        count = 0
        out += '\n'
print(out)
```

## Proof of work
<img width="max" alt="Screen Shot 2023-09-13 at 15 01 08" src="https://github.com/hasmhib/unit1-2024/assets/142870448/9bfc6a00-670d-4527-9cb2-773b1b291da1">

## Flow daiagram
![IMG_2A4C545FD5B2-1](https://github.com/hasmhib/unit1-2024/assets/142870448/9706961a-c103-4720-b802-ad710010def3)

