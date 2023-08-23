# This is a comment
"""
This class is about the basics of programming
Aug 23
"""
"""
#get imput from the user
first_name = input("Please enter your first name")
#output
print ("Hello", first_name)

#other types of variables
school = "uwcisak" #strings
year = 2023 #unmbers
height = 180.3 #float: decimal numbers
is_student = True

#get imput from the user
last_name = input("Please enter your last name")
#output
email = f"{year}.{first_name}.{last_name}@uwcisak.jp"
print (email)
"""
message = "welcome to the smartest tempurature converter"
print(message)
print("#"*len(message))
fahrenheit = input("enter the current tempurature in F")
#before converting we needto validate that the user know how to read
if fahrenheit.isdigit() == True:
    celcius = (int(fahrenheit) - 32)*5/9
    print(f"This tempurature is {celcius} C")
else:
    print("WRONG INPUT. USE DECIMAL NUMBERS".lower())


