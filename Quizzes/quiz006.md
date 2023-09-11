# Quiz 006
<img width="1503" alt="Screen Shot 2023-09-11 at 23 09 55" src="https://github.com/hasmhib/unit1-2024/assets/142870448/ad82337e-3ef8-4d87-8469-74890c16df03">

## Code

```py
#SL part
count = 0
for i in range(1,11):
    for j in range(1,11):
        count += 1
        if j ==10:
            print(f"{count}-Room {i}F{j}")
        else:
            print(f"{count}-Room {i}F0{j}")

#HL part
def locate_room(room_number: int) -> str:
    floor = room_number//10
    if floor == 0:
        floor = 1
    room = room_number % 10
    if room == 0:
        room = 10
    return f'{room_number}-Room {floor}F{room:02d}'
```

## Proof of work

```py
print('HL:', locate_room(26))
```

<img width="491" alt="Screen Shot 2023-09-12 at 0 13 44" src="https://github.com/hasmhib/unit1-2024/assets/142870448/5f634d04-28d6-478f-921c-9715ebf34a24">

