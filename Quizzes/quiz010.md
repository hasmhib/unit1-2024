# Quiz 009
<img width="max" alt="Screen Shot 2023-10-09 at 12 05 23" src="https://github.com/hasmhib/unit1-2024/assets/142870448/4703d064-7774-4d2d-b08d-4a5cafbd437e">

## Code for SL
```py

```

## Proof of work for SL


## Flow daigram


## Code for HL
```py
s = input("Input a number with unit: ")
n = [int(s) for s in s.split() if s.isdigit()]
powers = []
final = []
Units = ["Tera", "Giga", "Mega", "Kilo", "Unit", "Milli", "Micro", "Nano", "Pico"]
length_lmsg = 20


def power(n):
    count = 0
    for i in range(-12, 0, 3):
        temp = abs(i // 3)
        number = f"0.{(('000 ') * temp)}{str(n[0])} ".ljust(length_lmsg)
        powers.append(f"{number}{Units[count]}{s[1:]}")
        count += 1
    for i in range(0, 15, 3):
        temp = i//3
        number = f"{str(n[0])} {('000 '*temp)} ".ljust(length_lmsg)
        powers.append(f"{number}{Units[count]}{s[1:]}")
        count += 1

    return powers

print("\n".join(power(n)))

```

## Proof of work for HL
<img width="max" alt="Screen Shot 2023-10-09 at 12 09 46" src="https://github.com/hasmhib/unit1-2024/assets/142870448/3e6a5087-8773-49d0-93ac-8ac4f0faf17c">

## Flow diagram

