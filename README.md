# basiccalculator1.py
#python 2.7.15
import time
def main():
    print("///SELECT OPERATION///")
    print("1.add")
    print("2.substract")
    print("3.multiply")
    print("4.divide")
    choice = int(input("select choice 1/2/3/4\n"))

    num1 = int(input("enter first number>>>"))
    num2 = int(input("enter the second number>>>"))
    time.sleep(1)
    if choice == 1:
        def add(num1, num2):
            return num1 + num2;
        result = add(num1, num2)
        print(result)
        time.sleep(1)
    elif choice == 2:
        def substract(num1, num2):
            return num1 - num2;
        result1 = substract(num1, num2)
        print(result1)
        time.sleep(1)
    elif choice == 3:
        def multiply(num1, num2):
            return num1 * num2;
        result2 = multiply(num1, num2)
        print(result2)
        time.sleep(1)
    elif choice == 4:
        def divide(num1, num2):
            return num1 / num2;
        result3 = divide(num1, num2)
        print(result3)
        time.sleep(1)
    else:
        print("invalid input!!!!")
        time.sleep(1)
    print("enter 1 to restart")
    time.sleep(0.5)
    print("enter 2 to exit")
    time.sleep(0.5)
    restart = int(input("do you want to restart?\n"))
    time.sleep(2)
    if restart == 1:
        main()
    else:
        exit()
    
   
main()
time.sleep(3)
