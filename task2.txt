print("Simple Calculator")

num1 = int(input("Enter First Value  :"))
num2 = int(input("Enter Second Value :"))

choice = int(input("Enter Your Choice to Perform Basic Operations: \n 1.Addition \n 2.Subtraction \n 3. Multiplication \n 4. Division \n 5.Floor Division \n 6. Modulo Division \n 7.Exponential \n"))

if choice == 1:
    print("The Addition of {} and {} is : {}".format(num1,num2,num1+num2))
elif choice == 2:
    print("The Subtraction of {} and {} is : {}".format(num1,num2,num1-num2))
elif choice == 3:
    print("The Multiplication of {} and {} is : {}".format(num1,num2,num1*num2))
elif choice == 4:
    print("The Division of {} and {} is : {}".format(num1,num2,num1/num2))
elif choice == 5:
    print("The Floor Division  of {} and {} is : {}".format(num1,num2,num1//num2))
elif choice == 6:
    print("The Modulo Division  of {} and {} is : {}".format(num1,num2,num1%num2))
elif choice == 7:
    print("The Exponential of {} power {} is : {}".format(num1,num2,num1**num2))
else:
    print("Invalid Choice")
