# Quiz 003
<img width="max" alt="Screen Shot 2023-09-11 at 22 36 32" src="https://github.com/hasmhib/unit1-2024/assets/142870448/a09e5f22-e66c-43f6-94a8-bd00aa01f543">

## Code for Sl

```py
def DNA_translator(in_protein: str) -> str:
    # Check if the input protein is one of ATGC
    if in_protein in "ATGC":
        # Translate the input protein to its complement
        if in_protein == "A":
            out_protein = "T"
        elif in_protein == "G":
            out_protein = "C"
        elif in_protein == "T":
            out_protein = "A"
        elif in_protein == "C":
            out_protein = "G"
    else:
        # Handle the case when the input is not one of ATGC
        out_protein = "[error] Input is not one of ATGC"

    return out_protein

```

## Proof of work SL

```py
# Test case 1: Translate a single protein
case1 = DNA_translator(in_protein="A")
print(case1)
```
<img width="max" alt="Screen Shot 2023-09-12 at 1 13 23" src="https://github.com/hasmhib/unit1-2024/assets/142870448/99b5a0ef-54dd-4022-b3ec-8586887cf662">

## Code for HL

```py
def translatesequence(sequence: str) -> str:
    output_sequence = ""

    for p in sequence:
        # Translate each protein in the sequence
        print(f"Translating protein {p}")
        t = DNA_translator(in_protein=p)

        # Check if the translation result is a valid protein (ATGC)
        if t in 'ATGC':
            output_sequence += t
        else:
            # Handle the case when a protein is skipped
            print(f"[error] Protein {p} is skipped")

        print(f"Translating successful {output_sequence}")

    return output_sequence
```

## Proof of work HL

```py
# Test case 2: Translate a sequence of proteins
case2 = translatesequence(sequence="QAATTA")
print(case2)
```
<img width="max" alt="Screen Shot 2023-09-12 at 1 17 34" src="https://github.com/hasmhib/unit1-2024/assets/142870448/7725be00-3dfd-4082-9778-b9c0a9631021">



