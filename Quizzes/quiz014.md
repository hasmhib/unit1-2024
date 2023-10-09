# Quiz 014
<img width="max" alt="Screen Shot 2023-10-09 at 13 30 27" src="https://github.com/hasmhib/unit1-2024/assets/142870448/b8180a22-da44-4130-8a74-89318e417493">

## Code
```.py
def blackBoxThree(given:str):
    x = []
    for i in range(26):
        x.append(0)
    terms = "abcdefghijklmnopqrstuvwxyz"
    message = " "
    for y in range(len(given)):
        letter = given[y].lower()
        if letter == " ":
            message += " "
        for i in range(len(terms)):
            if letter == terms[i]:
                x[i] += 1
                message += f"{x[i]}"
    return(message)

out = blackBoxThree(given="hello world")
print(out)
out = blackBoxThree(given="aaaaAABB")
print(out)
out = blackBoxThree(given="abABabAB")
print(out)
out = blackBoxThree(given="Create a Function")
print(out)
```

## Proof of work
<img width="max" alt="Screen Shot 2023-10-09 at 22 14 49" src="https://github.com/hasmhib/unit1-2024/assets/142870448/9e991565-581f-4a3e-b14c-dae5a33be93f">


## Flow diagram
![IMG_093ED32D655B-1](https://github.com/hasmhib/unit1-2024/assets/142870448/c4f84541-5abe-4fe5-a603-8748d2dc9585)

