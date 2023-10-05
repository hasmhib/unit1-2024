# Crypto Wallet

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
I will to design and make a crypto wallet application for a client who is s a local trader. The crypto wallet will be about tracking crypto wallet transactions and is constructed using the software python. It will take 3 weeks to make and will be evaluated according to the criteria A.

** USD Coin (USDC) is a digital currency that is fully backed by U.S. dollar assets. USDC is a tokenized U.S. dollar, with the value of one USDC coin pegged as close to the value of one U.S. dollar as it can get. The value of USDC is designed to remain stable, making USDC a stablecoin. **

citations : https://www.investopedia.com/usd-coin-5210435#:~:text=USD%20Coin%20(USDC)%20is%20a,stable%2C%20making%20USDC%20a%20stablecoin. 

## Why USD crypto coin?

1. Price Stability: The main benefit of this USD coins is that their prices remain stable. USD coins can be the best choice if the users wants to make transactions or hold value without being concerned about big price changes.
2. Trading pairs: USD coins trading pairs are available on many cryptocurrency exchanges, allowing you to instantly deposit or withdraw without having to swap your coins for fiat money. This may be advantageous to traders.
3. Cross-Border Transactions: USD ecoins can make international transfers and cross-border transactions easier since US dallar is very stable. This allows you to send and receive money without worrying about changing exchange rates.

## Why Python?

1. Flexibility and versatility Python provides excellent code, input, and imported item flexibility, ensuring multipurpose features. Enabling special features like real-time updates on a specific item. In Ms. Sato's situation, it aims her in keeping track of the coin's value.
2. Interface Python features a user-friendly, intuitive interface that makes it simple to code, work in the terminal, and run and test the code. It has a numerous number of integrated libraries and tools make coding simpler and more time-effective. All of this makes it simple for Ms. Sato to read and use the electronic ledger.
3. Preservation and readable Software upgrades and maintenance are easy to handle and the bug appearing in the code is much less because Python is so flaxible with various functions. Because it enables all of these possibilities to be implemented in a straightforward system with easy-to-understand, clear, and easy syntax. This guarantees that Ms. Sato will benefit from this electronic ledger for a very long time, that will be easier to upgrade and expand further.


## Success Criteria
1. The electronic ledger is a text-based software (Runs in the Terminal).
2. The electronic ledger display the value in Japanese Yen, date created and the number of users of the cyrptocurrency selected.
3. The electronic ledger allows to enter, withdraw and record transactions.
4. The electronic ledger sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others)
5. Only the client has an access to the electronic ledger.
6. The electronic ledger allows the user to set the limit for amount of cryptocurrency to spend per month. 

# Criteria B: Design

## System Diagram

<img width="max" alt="Screen Shot 2023-10-05 at 2 58 16" src="https://github.com/hasmhib/unit1-2024/assets/142870448/5b5d43d1-1065-4c35-8448-fd8b32f8e188">
Fig 1. System diagram for the cryptocurrency wallet. It shows the input/output and software/hardware, and how the program runs on Python as well as the different databases the code exchanges information.

## Test plan

|              Test Type             |                                                                          Target                                                                         |                                                                                  Procedure                                                                                 |                                                                                                                                                                                            Expected Outcome                                                                                                                                                                                            |
|:----------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|      Functional: Unit testing      |                                                                   validate_int_input.                                                                   |                                 1. Use the function validate_int_input 2. Enter "S" in the terminal 3. Enter a number in the terminal                                 |                                                                                                                                                  1. With a letter an error message will be print 2. With a number the program will output the number.                                                                                                                                                  |
|  Functional: Integrational testing |                                                                     Sign up system.                                                                     |                                            1. Use the sign up register. 2. Enter a desired username "Bob" and password "bob123" in the terminal                                           |                                                                                          After entering a desired username and password, the crendtials should go into a database file to store the credentials. It should also print "Registeration Successful!" after the username and password is entered.                                                                                          |
|  Functional: Integrational testing |                                                                      Login system.                                                                      |                                        1. Use the function login. 2. Enter your credentials (username and password) in the terminal                                        |                                                                                                                With the correct username and password input, the code should proceed to show the menu. In any other cases, access must be denied to the user and the program will exit.                                                                                                                |
| Functional : Integrational testing |                                                                  Create a transaction.                                                                  | 1. Choose to create a transaction 2. Enter expense category "1 for Food". 3. Enter expense amount, price "100 USD" 5. Choose to view transaction history | When the transaction function is activated, the user should be provided with an option to choose how much cryptocurrency, on what purpose[Food, Groceries, Transport, Cosmetics, Clothes, Subscriptions, Others. Along with the date of the input, the program will input these data "100 USD" into the "atm.csv" where all transactions are recorded and organized, where datasets are made easily accessible.  |
|    Non-functional: Load testing    | Testing if transaction history shows all data without any glitches or bugs. Additionally, all newly inputted transaction data should be displayed well. |                            1. Login to the Crypto Wallet 2. Select Create or View Transaction History option 3. Select View transaction history                            |                                                                  All information in the list should be falling in the appropriate column and row. All datasets must be in the appropriate location and be correct and accurate from the data. Furthermore, any new transactions the user inputted should be added to the spreadsheet.                                                                  |
| Non-functional: Usuability testing |                         The login instructions and options displayed in main menu after logging in are clear and easy to follow.                        |                                                                           1. Run program 2. Login                                                                          |                                                                                                                                         The login and sign in instructions are clear, and the main menu items can be easily read, identified, and understood.                                                                                                                                          |
|    Non-functional: Response time   |                                                  Testing if code responds to user interaction promptly                                                  |                                     1. Login to the Crypto Wallet 2. Choose any options and follow the prompted directions that follow                                     |                                                                                                                                    There are no bugs and errors with the code, and the program sustains a prompt respond with accurate informations from databases.                                                                                                                                    | 

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

<img width="max" alt="Screen Shot 2023-10-05 at 12 37 31" src="https://github.com/hasmhib/unit1-2024/assets/142870448/64d61141-ff00-4852-8b5e-2261ad09cf45">

Fig 2. The flow diagram for the sign up system where clients can create an account and start using sing the cryptocurrency wallet. It receives inputs from the user, opens up a csv file named "users.csv" and appends that data into the database if the given password and the confirmation password matches. When that is successfully complete, it will notify the user and proceeds to ask if they would like to exit or continue to login. if exit, it will execute exit(), and if login, it will execute the login() function. 


<img width="max" alt="Screen Shot 2023-10-05 at 12 38 31" src="https://github.com/hasmhib/unit1-2024/assets/142870448/926de715-bd53-4296-bbef-b303f4b7f8cd">

Fig 3. The flow diagram for a code that ensures that the client is not spending above the monthly limit that they imposed on themselves. The code first opens two csv files, one being the “atm.csv” where all the transactions are recorded, and the “limit.csv” where the monthly limit that they client implemented is recorded. When the client attempts to withdraw cryptocurrency, the system will first add the amount of cryptocurrency to the withdraw_balance variable, where the amount of cryptocurrency spent that month is accumulatively recorded. Next, it will ensure that the withdraw_balance does not exceed the monthly limit imposed, and if it does, it will print the message “Sorry, you have reached the limit to spend this month.”


<img width="max" alt="Screen Shot 2023-10-05 at 12 39 06" src="https://github.com/hasmhib/unit1-2024/assets/142870448/d9448a80-fb94-471b-9f0c-38559dc0999c">

Fig 4. The flow diagram for the deposit function of this system. It will ask for the amount that the user wants to deposit first, and then integer validate that input to ensure that its s a number and not an alphabet. Then, it will convert that input to Japanese yen and append that transaction data into the atm.csv file with its original cryptocurrency amount and yen conversion. When successfully completed the code will print “Saved” and return to the menu.


# Criteria C: Development

## Technique used
1. Functions
2. For/While loops
3. If/else statements
4. List Comprehinsion

## User Registration
```.py
email = input("Enter email address: ")
password = input("Enter password: ")
conf_pwd = input("Confirm password: ")
if conf_pwd == password:
    with open("users.csv", "a") as file:
        file.write(f"{email},{conf_pwd}\n")
    file.close()
    print("You have registered successfully!")
    exit_login = input("Would you like to exit(x) or login?(l):")
    if exit_login=="x":
        exit()
    elif exit_login=="l":
        login()
else:
    print("Password is not same as above! \n")
```
The first part of creating a digital ledger for a client is to create a registration system so the client can create a Crypto Wallet account. This code allows the user to enter a username and password they desire, "Bob, bob123" and it adds their crendentials into a file if the if statement of confirming whether the provided password and confirmation password matches is true. Registered users will be able to login afterwards, and use the functions provided by this program. When registeration is complete, users are given two options of whether exiting the program or continuing to a login screen. This is also coded with if,elif statements. 


## Option 1: Deposit
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
The client wants to be able to deposit USD coins into their cryptocurrency wallet "100 USD". This code asks the user for the amount of USD coins they would like to deposit to their wallet, and records a transaction of the respective deposition into the atm.csv file "USD coins into atm.csv file". Informations such as date of the depsition and JPY conversion of the USD coins are also provided as record. 


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
My client wants to sort transactions by category (food, transport, cosmetics, clothes, subscriptions and others) so I used while loop and brackets [] to allow users to sort transactions by using number that corresponds to the numbers on the list. Also, by using option 6, the user enables to set the limit amount of cryptocurrency per month and ensure that her spendigns will not exceed her expected expenditure unwillingly. This code effectively processes financial transactions, keeps track of the user's spending, and prevents them from exceeding their monthly limit. It also records transactions in a atm.csv file for future reference. "if category != "Deposit" and date[5:7] == current_month:" At first, I was challenged to figure out this, but I figured out by using brackets[] to check the month. In here, atm.csv file saves like this "2023-10-05,Deposit,100,14530.0". If category, which is next to the YYYY, MM, DD, not "Deposit", which means that these tranactions are withdraw, so we have to calculate how many the user spent that month. This "date[5:7]" corresponds to the month, in this case "10", to categorize what month did the user spent the money and to check whether the limit that user set is smaller than the amount they used during the month. 


## Option 4: Transaction history
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
The code above prints out the users recorded transactions into an organized spreadsheet. This will allow the client to easliy see all of their past transaction data. It is simple and visually appealing. It is able to print all recent transactions created by the user by using a for loop. With the for loop, it will continue to go through the data in the "atm.csv" file and print the data into an organized spreadsheet with all the data in the appropiate column until there is no more data to print. It makes sure each piece of information is placed in the correct column to prevent disorganization.

## Option 5: Set the limit of cryptocurrency to use per month

```.py
limit = int(input("Please enter the limit.csv of cryptocurrency to spend per month: "))
        with open("limit.csv", "w") as l:
            l.writelines(f"{limit}")
            print("Limit is set, thank you!")
        l.close()
        menu()
```
As the client does not want to spend more than they have, they wanted a monthly limit. At first, this was a challenge, because I did not know how to restrict the withdrawal of balance. However, after doing my due diligence and research, I learned how to set limits through basic user inputs and if statements. First, we ask the imput to the user and convert to integer. The line "with open("limit.csv", "w") as l:" This code needs to rewrites the limit per month when the user executes this code, so I used write mode ("w") instead of append mode ("a"). And open limit.csv file and convert "limit" values to "f string" to write it as a line in the file. Then the code prints "Limit is set, thank you!" to notify the users that the program successfully set the limit of cryptocurrency for the month.  

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
