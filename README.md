f1 = input("Enter your first fruit ")
f2 = input("Enter your second fruit ")
f3 = input("Enter your third fruit ")
fruit_list = [f1,f2,f3]
print("The current items are", fruit_list)
ask = input("Do you want to add something? ")
if ask == "yes":
    a=input("What do you want to add? ")
    fruit_list.append(a)
    print("The updated list is", fruit_list)
else:
    print("Ok")
