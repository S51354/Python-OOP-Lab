# Python-OOP-Lab
pincode = input ("Enter pincode =")
pincode = int (pincode)

if pincode == 0:
   print("WRONG PIN")
elif pincode == 1111:
   print("CORRECT PIN")
else:
   print("WRONG PIN")

class Bank_Account: 

    def __init__(self): 
        self.balance=0
        print("Your current acc balance is $", self.balance) 
  
    def deposit(self): 
        amount=float(input("Enter amount to be Deposited: $")) 
        self.balance += amount 
        print("\n Amount Deposited:",amount) 
  
    def withdraw(self): 
        print("You can only withdraw less than $100000")
        amount = float(input("Enter amount to be Withdrawn: $")) 
        if self.balance>=amount: 
            self.balance-=amount 
            print("\n You Withdrew: $", amount) 
        else: 
            print("\n Insufficient balance  ") 
  
    def display(self): 
        print("\n Net Available Balance= $",self.balance) 
        
class TestClass():
    def pinChange(self):
        global pincode
        pincode = input ("Enter new pincode =")
        print("Your new pincode is set up as",pincode)

TestClass().pinChange()

s = Bank_Account() 

s.deposit() 
s.withdraw() 
s.display() 
