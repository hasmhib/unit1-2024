# Crypto Wallet

![](22ROOSE-master768.gif)  
<sub>Illustration for Glenn Harvey</sub>

# Criteria A: Planning

## Problem definition

Ms. Sato is a local trader who is interested in the emerging market of cryptocurrencies. She has started to buy and sell electronic currencies, however at the moment she is tracking all his transaction using a ledger in a spreadsheet which is starting to become burdensome and too disorganized. It is also difficult for Ms Sato to find past transactions or important statistics about the currency. Ms Sato is in need of a digital ledger that helps her track the amount of the cryptocurrency, the transactions, along with useful statistics. 

Apart for this requirements, Ms Sato is open to explore a cryptocurrency selected by the developer.
| Name   | Coin            |   | Name | Coin |
|--------|-----------------|---|------|------|
| Keeler | ETH             |   |      |      |
| Rocky  | DOGE            |   |      |      |
| Yuiko  | BNB(Binance)    |   |      |      |
| Jan    | Tether (USDT)   |   |      |      |
| Antoni | XRP(Ripple)     |   |      |      |
| Victor | Cardano (ADA)   |   |      |      |
| Manaha | LTC (LIte Coin) |   |      |      |
| Marina | Solano (SOL)    |   |      |      |
| May    | (DAI)           |   |      |      |
| Ayane  | Zcash (ZEC)     |   |      |      |
An example of the data stored is 

| Date | Description | Category | Amount  |
|------|-------------|----------|---------|
| Sep 23 2022 | bought a house | Expenses | 10 BTC |
| Sep 24 2022 | food for house celebration | Food | 0.000001 BTC |


## Proposed Solution

Design statement:
I will to design and make a crypto wallet application for a client who is s a local trader. The crypto wallet will be about tracking crypto wallet transactions and is constructed using the software python. It will take 3 weekns to make and will be evaluated according to the criteria A.

** USD Coin (USDC) is a digital currency that is fully backed by U.S. dollar assets. USDC is a tokenized U.S. dollar, with the value of one USDC coin pegged as close to the value of one U.S. dollar as it can get. The value of USDC is designed to remain stable, making USDC a stablecoin. **

citations : https://www.investopedia.com/usd-coin-5210435#:~:text=USD%20Coin%20(USDC)%20is%20a,stable%2C%20making%20USDC%20a%20stablecoin. 

Justify the tools/structure of your solution

## Success Criteria
1. The electronic ledger is a text-based software (Runs in the Terminal).
2. The electronic ledger display the value in Japanese Yen, date created and the number of users of the cyrptocurrency selected.
3. The electronic ledger allows to enter, withdraw and record transactions.
4. The electronic ledger sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others)
5. Only the client has an access to the electronic ledger.
6. The electronic ledger allows the user to set the limit for amount of cryptocurrency to spend per month. 

# Criteria B: Design

## System Diagram

<img width="max" alt="Screen Shot 2023-10-03 at 23 08 04" src="https://github.com/hasmhib/unit1-2024/assets/142870448/c6bcbaae-e1d9-4958-8126-835b4937d8ff">
 

## Record of Tasks
| Task No | Planned Action                         | Planned Outcome                                                                          | Time estimate | Target completion date | Criterion |
|---------|----------------------------------------|------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Create system diagram                  | To have a clear idea of the hardware and software requirements for the proposed solution | 10min         | Sep 14                 | B         |
| 2       | Create flow diagram for login function | A flow diagram and the code tested                                                       | 30min         | Sep 14                 | B,C       |
| 3       | Create a simple registration and login system | To create a program that allows the user to register and login to their digital ledger using a username and password they created. | 1 hour | Sep 26  | C       |
| 4       | Code menu options and allow user interaction | Code that can sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others) to allow users to sort transactions by using number that corresponds to the numbers on the list.  | 2 hours | Sep 27  | C       |
| 5       | Code a menu for deposit and withdraw | Code option 1 and 2 to allow users to save the amount of deposit and withdraw. This data will saved in atm.csv. | 1 hour | Sep 27  | C       |
| 6       | Code a display to show the balance after money is either deposited or withdrawn | Code a function that would add or subtract the amount of money deposited or withdrawn from the balance and print the updated balance | 30 min | Sep 29  | C       |
| 7       | Create a visual graph for transaction data | Code that creates the graph of how much the user spent. | 1 hour | Sep 29  | C       |
| 8       | Create a visual display for transaction data | Print total balance, total money in and total money out to visualize the transactions. | 1 hour | Sep 29  | C       |


# Criteria C: Development

## Login System
My client requires a system to protect the private data. I thought about using a login system to accomplish this requirement using a if condition and the open command to work with a csv file.

The flow diagram for program is shown in **Figure1** in the first line of the code. I am defining a function called try_login with two inputs (name and password) ,both are type string. The output is boolean because I only need a True if the user and password exist in the database file. Note: there is some Python code in the operations.

**Figure1**
![IMG_0020](https://github.com/hasmhib/unit1-2024/assets/142870448/73cb0e76-25a0-4fe6-abee-05a2562b329c)


```.py
def try_login(name:str, password:str)->bool:
    with open("users.csv", mode='r') as f:
        data = f.readlines()
    logged_in = False
    for line in data:
        uname = line.split(',')[0]
        upass = line.split(',')[1].strip()

        if uname == name and upass == password:
            logged_in = True
            break
    return logged_in

attempts = 3
name = input("Please enter your username")
password = input("Please enter your password")
result = try_login(name = name,password = password)
while result == False and attempts>0:
    name = input("[Error] Please enter your username")
    password = input("Please enter your password")
    result = try_login(name=name, password=password)
    attempts -= 1

if result == False:
    print("You are not authorized. Exiting")
    exit(1)

if result == True:
    print("Welcome")
```

## Option 1: Deposit
My cleint 
```.py
```

## Option 2: Withdraw
My client wants to sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others) so I used while loop and brackets [] to allow users to sort transactions by using number that corresponds to the numbers on the list. 

```.py
```

## Option 3: Balance
```.py
```

## Option 5: Transactions
The code above prints out the users recorded transactions by using for loop. This will allow the client to easliy see all of their past transaction data. It is simple and visually appealing. With the for loop, it will continue to go through the data in the "atm.csv" file and print the data into an organized spreadsheet with all the data in the appropiate column until there is no more data to print. It makes sure each piece of information is placed in the correct column to prevent disorganization.
```.py
```

## Set the limit of cryptocurrency to use per month
```.py
```
