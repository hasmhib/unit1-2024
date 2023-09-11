# Quiz 003
<img width="max" alt="Screen Shot 2023-09-11 at 22 36 32" src="https://github.com/hasmhib/unit1-2024/assets/142870448/a09e5f22-e66c-43f6-94a8-bd00aa01f543">

## Code

```py
def DNA_translator(in_protein:str)->str:
    if in_protein in "ATGC":
        if in_protein == ("A"):
            out_protein = "T"
        if in_protein == ("G"):
            out_protein = "C"
        if in_protein == ("T"):
            out_protein = "A"
        if in_protein == ("C"):
            out_protein = "G"

    else:
        out_protein = "[error]input is not one of ATGC"

    return out_protein

def translatesequence(sequence:str)->str:
    output_sequence = ""
    for p in sequence:
        print(f"Translating proten {p}")
        t = DNA_translator(in_protein=p)
        if t in 'ATGC':
            output_sequence += t
        else:
            print("[error]protein {p} is skipped")

        print(f"Translating successful {output_sequence}")

    return output_sequence
```

## Proof of work

```py
case1 = DNA_translator(in_protein="A")
print(case1)


case2 = translatesequence(sequence = "QAATTA")
print(case2)
```

<img width="max" alt="Screen Shot 2023-09-11 at 22 39 22" src="https://github.com/hasmhib/unit1-2024/assets/142870448/b36cdc52-de3c-4b98-966e-c91a73c5356e">
