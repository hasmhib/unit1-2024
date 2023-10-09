# Quiz 015
<img width="max" alt="Screen Shot 2023-10-09 at 13 49 56" src="https://github.com/hasmhib/unit1-2024/assets/142870448/f9b1d275-f268-4732-8a85-9f7648ac7ce8">

# Code 
```.py
def open_doors(num_students:int):
    doors = []
    for i in range(num_students):
        doors.append(False)
    for stu in range(1, num_students + 1):
        for door in range(1, num_students + 1):
            if door % stu == 0:
                doors[door - 1] = not doors[door - 1]
    open = 0
    closed = 0
    for fact in doors:
        if fact == True:
            open += 1
        else:
            closed += 1
    return f"Open doors: {open}, Closed doors: {closed}"

out = open_doors(10)
print(out)

out = open_doors(100)
print(out)

out = open_doors(200)
print(out)

out = open_doors(5678)
print(out)
```

# Proof of work
<img width="max" alt="Screen Shot 2023-10-09 at 13 56 26" src="https://github.com/hasmhib/unit1-2024/assets/142870448/c4c557e5-7bdf-4306-858e-392479aad397">

## Flow diagram
![Uploading IMG_C9298C05DE6B-1.jpeg…]()







