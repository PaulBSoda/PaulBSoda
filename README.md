
def add():
    a = float(input("Enter first number: "))  
    b = float(input("Enter second number: "))
    c = a + b  
    print("result = ", c)

def sub():
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    c = a - b
    print("result = ", c)

def mult():
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    c = a * b
    print("result = ", c)

def div():
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    c = a / b
    print("result = ", c)
    
while True:
    print('1.+')
    print('2.-')
    print('3.*')
    print('4./')
    choice = input("select the number of operation:")
    if int(choice) == 1:
        print(add())
    elif int(choice) == 2:
        print(sub())
    elif int(choice) == 3:
        print(mult())
    elif int(choice) == 4:
        print(div())
    else:
        print("Error, try again")
        continue
    while True:
        con = input("continue?:")
        if con == "yes":
            break
        elif con == "no":
            exit(0)
        else:
            print("i dont understand, try again")
