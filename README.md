while True:
    a=int(input("Whats the first number?: "))
    print("+\n-\n*\n/")
    user=input("pick an operation: ")


    if user in ["+", "-", "*", "/"]:
        b=int(input("Whats the next number?:"))

        if user == "+":
            print(f"{a}+{b}=",a+b)
        elif user=="-":
            print(f"{a}-{b}=",a-b)
        elif user =="*":
            print(f"{a}*{b}=",a*b)
        elif user == "/":
            print(f"{a}/{b}=",a/b)
    else:
        print("Invalid Operation")
    choice = input("Do you want to continue? (yes/no): ")
    if choice.lower()=="yes":
        continue
    elif choice.lower()=="no":
        break


