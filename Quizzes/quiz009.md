# Quiz 009

## Code for SL
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

## Proof of work for SL
<img width="max" alt="Screen Shot 2023-09-13 at 15 01 08" src="https://github.com/hasmhib/unit1-2024/assets/142870448/9bfc6a00-670d-4527-9cb2-773b1b291da1">

## Code for HL
```py
```

## Proof of work for HL
