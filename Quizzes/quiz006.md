# Quiz 006
<img width="max" alt="Screen Shot 2023-09-11 at 23 09 55" src="https://github.com/hasmhib/unit1-2024/assets/142870448/ad82337e-3ef8-4d87-8469-74890c16df03">

## Code for SL

```py
# SL part
count = 0

# Loop through the floors (i) and rooms (j) from 1 to 10
for i in range(1, 11):
    for j in range(1, 11):
        count += 1  # Increment the count for each room
        
        # Check if the room number is 10 and print accordingly
        if j == 10:
            print(f"{count}-Room {i}F{j}")
        else:
            print(f"{count}-Room {i}F0{j}")
```

## Proof of work for SL

<img width="max" alt="Screen Shot 2023-09-12 at 2 06 38" src="https://github.com/hasmhib/unit1-2024/assets/142870448/7d51b5d8-817b-4e14-9877-bb649c3f2d16">


## Code for HL

```py
def locate_room(room_number: int) -> str:
    # Calculate the floor number and ensure it's at least 1
    floor = room_number // 10
    if floor == 0:
        floor = 1
    
    # Calculate the room number and ensure it's between 1 and 10
    room = room_number % 10
    if room == 0:
        room = 10
    
    # Create the output string with the room number, floor, and room formatted with leading zeros
    return f'{room_number}-Room {floor}F{room:02d}'

```

## Proof of work for HL

```py
print('HL:', locate_room(26))
```
<img width="max" alt="Screen Shot 2023-09-12 at 2 07 50" src="https://github.com/hasmhib/unit1-2024/assets/142870448/e10aebb5-bf7a-4a37-b8e4-6d82d2a08ee3">


