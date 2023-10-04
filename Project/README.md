# Crypto Wallet

![](22ROOSE-master768.gif)  
<sub>Illustration for Glenn Harvey</sub>

# Criteria A: Planning

## Problem definition

Ms. Sato is a local trader who is interested in the emerging market of cryptocurrencies. She has started to buy and sell electronic currencies, however at the moment she is tracking all his transaction using a ledger in a spreadsheet which is starting to become burdensome and too disorganized. It is also difficult for Ms Sato to find past transactions or important statistics about the currency. Ms Sato is in need of a digital ledger that helps her track the amount of the cryptocurrency, the transactions, along with useful statistics. 

### Example
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
Fig 1. System diagram for the cryptocurrency wallet. It shows the input/output tput and software/hardware, and how the program runs on Python as well as the different databases the code exchanges information.
 

## Record of Tasks
| Task No |                                     Planned Action                                    |                                                                                                               Planned Outcome                                                                                                              | Time estimate | Target completion date | Criterion |
|:-------:|:-------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------:|:----------------------:|:---------:|
| 1       | Meet with the client                                                                  | Have a meeting with the client and identify their problems. Brainstorm solutions and establish a plan to help resolve the client's problem.                                                                                                | 20 min        | Sep 14                 | A         |
| 2       | Write out the problem definition                                                      | Clarify and write out the problem definition on the repositiory.                                                                                                                                                                           | 15 min        | Sep 14                 | A         |
| 3       | Write out proposed solution for the client                                            | Brainstorm and clarify the justification of the resolution to client's problem.                                                                                                                                                            | 15 min        | Sep 14                 | A         |
| 4       | Define and write out success criteria                                                 | Clarify and write out the success criteria discussed and decided with client to resolve their problem.                                                                                                                                     | 15 min        | Sep 14                 | A         |
| 5       | Create system diagram                                                                 | To have a clear idea of the hardware and software requirements for the proposed solution.                                                                                                                                                  | 30 min        | Sep 14                 | B         |
| 6       | Create a simple sign-up (registration) and login system                               | A flow diagram and the code tested.                                                                                                                                                                                                        | 30 min        | Sep 14                 | B,C       |
| 7       | Write a flow diagram for the signup system                                            | To create a program that allows the user to register and login to their digital ledger using a username and password they created.                                                                                                         | 1 hour        | Sep 26                 | C         |
| 8       | Code menu options for crypto wallet and allow user interaction                        | The user can choose different options from the menu (Ex: Option 1: Deposit, and the user will be able to choose Option 1 to deposit the money).                                                                                            | 2 hours       | Sep 27                 | C         |
| 9       | Code a menu for "deposit" and "withdraw" options                                      | Code option 1 and 2 to allow users to save the amount of deposit and withdraw. This data will saved in atm.csv.                                                                                                                            | 1 hour        | Sep 27                 | C         |
| 10      | Code a display to show the "balance" option of the crypto wallet                      | Code a function that would add or subtract the amount of money deposited or withdrawn from the balance and print the updated balance.                                                                                                      | 30 min        | Sep 29                 | C         |
| 11      | Code a system that converts USDC crypto-coin into Japanese Yen and apply it to wallet | Import currency rates to convert USD coin into Japanese Yen.                                                                                                                                                                               | 1 hour        | Sep 29                 | C         |
| 12      | Create a visual display for "transaction data" option                                 | Print total balance, total money in and total money out to visualize the transactions.                                                                                                                                                     | 1 hour        | Sep 29                 | C         |
| 13      | Code transaction functions (deposit and withdraw functions)                           | Create a code that allows the user to record when they made the transaction, what kind of transaction it was, and how much the transaction was. The code will then transfer all of that information into a spreadsheet with accurate data. | 2 hour        | Sep 29                 | C         |
| 14      | Code the "Set Limit" function where users can set monthly crypto currency spend       | Code option 5 that the users can set the limit of cryptocurrency to spend per month.                                                                                                                                                       | 1 hour        | 0ct 2                  | B         |
| 15      | Create a system that the user can set the limit of cryptocurrency to spend per month  | Check every time if they want to withdraw a money and if the amount they used during a month does not go over the amount they set.                                                                                                         | 2 hour        | 0ct 2                  | B         |
| 16      | Double-check all functions and validate user input for all option choices             | Double-check all functions and debug if any bug is found; code function that would validate the input and ensure that the input is a numerical input.                                                                                      | 1 hour        | Oct 3                  | B         |
| 17      | Draw and describe the flow diagrams                                                   | Flow diagrams for the different codes, and some brief explanations.                                                                                                                                                                        | 1 hour        | 0ct 4                  | B         |
| 18      | Write the test plans                                                                  | Procedures one should take to test the program and the expected outcome of each test is on Github.                                                                                                                                         | 1 hour        | 0ct 4                  | B         |
| 19      | Meet with the client                                                                  | Hear feedback from the client about the product I made.                                                                                                                                                                                    | 30 min        | Oct 4                  | B         |
| 20      | Finish Criteria C                                                                     | Write the description and insert a flow chart of the codes and the details of the code that was used on GitHub.                                                                                                                            | 2 hours       | Oct 4                  | C         |

## Flowcharts

![386459934_1200604738009110_2348546487285065411_n](https://github.com/hasmhib/unit1-2024/assets/142870448/5df7cdc9-2276-49d6-8a6b-2a0f7b2ab4a8)
Fig 2. The flow diagram for the sign up system where clients can create an account and start using sing the cryptocurrency wallet. It receives inputs from the user, opens up a csv file named "users.csv" and appends that data into the database if the given password and the confirmation password matches. When that is successfully complete, it will notify the user and proceeds to ask if they would like to exit or continue to login. if exit, it will execute exit(), and if login, it will execute the login() function. 

![386863920_1626443091098644_456211345082400213_n](https://github.com/hasmhib/unit1-2024/assets/142870448/b4e595bf-8e7d-40f0-8f69-0590266a418c)
Fig 3. The flow diagram for a code that ensures that the client is not spending above the monthly limit that they imposed on themselves. The code first opens two csv files, one being the “atm.csv” where all the transactions are recorded, and the “limit.csv” where the monthly limit that they client implemented is recorded. When the client attempts to withdraw cryptocurrency, the system will first add the amount of cryptocurrency to the withdraw_balance variable, where the amount of cryptocurrency spent that month is accumulatively recorded. Next, it will ensure that the withdraw_balance does not exceed the monthly limit imposed, and if it does, it will print the message “Sorry, you have reached the limit to spend this month.”

![384547502_833611304885865_6744060710249008360_n](https://github.com/hasmhib/unit1-2024/assets/142870448/69210792-6951-48bb-9527-7bfe17c87076)
Fig 4. The flow diagram for the deposit function of this system. It will ask for the amount that the user wants to deposit first, and then integer validate that input to ensure that its s a number and not an alphabet. Then, it will convert that input to Japanese yen and append that transaction data into the atm.csv file with its original cryptocurrency amount and yen conversion. When successfully completed the code will print “Saved” and return to the menu.




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

## Option 1: User Registration
My cleint 
```.py
def register(uname:str, password:str):
    file = open("credentials.csv", "a")
    salty = "computerscience"
    to_hash = uname + password + salty
    hashed_password = hmac.new(''.encode(), to_hash.encode(), 'sha512').hexdigest()
    file.write(f"{uname},{hashed_password}\n")
```
The first part of creating a digital ledger for a client is to create a registration system so the client can create a Crypto Wallet account. This code allows the user to enter a username and password they desire, and it adds their crendentials into a file with and encrypted password. The encryption I used in this is called "hashing". Encryption is the process of encoding plain text or any information in such a way that only authorized people can read it with a corresponding key, like a password, so that confidential data can be protected from unauthorized persons. Hashing converts any amount of data into a fixed-length hash that cannot be reversed. In my code, it is hashed using a random string of characters, known as a salt. This is an additional input to my code above to hash the user's password.

## Option 2: Withdraw
```.py
 if option == 2:  # withdraw
        amount = int(input("Enter the amount($): "))  # Convert amount to an integer
        categories = ["Foods", "Groceries", "Transport", "Cosmetics", "Clothes", "Subscriptions", "Others"]
        print_menu(categories)
        category_new = -1
        while category_new not in [1, 2, 3, 4, 5, 6]:
            category_new = validate_int_user(msg="Enter an option: ", menu=categories)

        with open('atm.csv', mode='r') as f:
            data = f.readlines()

        withdraw_balance = 0

        with open("limit.csv", mode="r") as f:
            limit = f.readlines()

        now = datetime.datetime.now()
        current_month = now.strftime('%m')

        for line in data:
            date, category, line_amount, yen = line.strip().split(',')
            line_amount = int(line_amount)  # Convert the line_amount to an integer
            if category != "Deposit" and date[5:7] == current_month:
                withdraw_balance += abs(line_amount)  # Accumulate as positive

        # Check if the user exceeds the limit
        if withdraw_balance + amount <= int(limit[0]):
            with open('atm.csv', mode='a') as w:
                today = datetime.date.today()
                yen = round(145.3 * amount, 2)
                line = f"{today},{categories[category_new - 1]},{-amount},{yen}\n"  # Save amount as negative
                w.writelines(line)
                print("Saved, thank you!")
                menu()
            w.close()
        else:
            print("Sorry, you have reached the limit to spend this month.")
            menu()
```
My client wants to sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others) so I used while loop and brackets [] to allow users to sort transactions by using number that corresponds to the numbers on the list. Also, by using option 6, the user enables to set the limit amoount of cryptocurrency per month and 

## Option 3: Balance
```.py
msg_deposit = "Enter amount to deposit($): "
amount = validate_int_user(msg=msg_deposit, menu="")
date = datetime.date.today()
yen = round(145.3 * int(amount), 2)
with open('atm.csv', mode='a') as f:
    line = f"{date},Deposit,{amount},{yen}\n"
    f.writelines(line)
print("Saved")
menu()
```

## Option 4: Transactions
```.py
    if option == 4:  # transactions
        with open('atm.csv', mode='r') as f:
            print("Transaction History:")
            print("{:<12} {:<15} {:<10} {:<10}".format("Date", "Category", "Amount", "Yen(Convertion)"))
            print("=" * 49)

            for line in f:
                date, category, amount, yen = line.strip().split(',')
                amount = int(amount)
                yen = float(yen)  # Convert Yen to float for readability

                print("{:<12} {:<15} {:<10} {:<10}".format(date, category, amount, yen))

            print("=" * 49)
        menu()
```
The code above prints out the users recorded transactions into an organized spreadsheet. This will allow the client to easliy see all of their past transaction data. It is simple and visually appealing. It is able to print all recent transactions created by the user by using a for loop. With the for loop, it will continue to go through the data in the "sheet.csv" file and print the data into an organized spreadsheet with all the data in the appropiate column until there is no more data to print. It makes sure each piece of information is placed in the correct column to prevent disorganization.

## Option 5: Set the limit of cryptocurrency to use per month

```.py
limit = int(input("Please enter the limit.csv of cryptocurrency to spend per month: "))
        with open("limit.csv", "w") as l:
            l.writelines(f"{limit}")
            print("Limit is set, thank you!")
        l.close()
        menu()
```
As the client does not want to spend more than they have, they wanted a monthly limit. At first, this was a challenge, because I did not know how to restrict the withdrawal of balance. However, after doing my due diligence and research, I learned how to set limits through basic user inputs and if statements. 

```.py
if withdraw_balance + amount <= int(limit[0]):
    with open('atm.csv', mode='a') as w:
        today = datetime.date.today()
        yen = round(145.3 * amount, 2)
        line = f"{today},{categories[category_new - 1]},{-amount},{yen}\n"  # Save amount as negative
        w.writelines(line)
        print("Saved, thank you!")
        menu()
    w.close()
else:
    print("Sorry, you have reached the limit to spend this month.")
    menu()
```
By employing an if statement in the withdraw system, I was able to successfully implement a monthly limit to how much cryptocurrency is spent. The client is able to set this limit themselves. 
