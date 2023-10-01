```python
pin=1234
amount=10000
user_pin=int(input("Enter the pin Number:"))
if user_pin==pin:
    print("1.Deposite\n2.Withdrwal\n3.BalanceEnquiry")
    ch=int(input("Enter Your Choice"))
    if ch==1:
        damount=int(input("Enter the Deposite amount"))
        amount=amount+damount
        print("Your available balance",amount)
    elif ch==2:
        wamount=int(input("Enter the Withdrwal amount"))
        amount=amount+wamount
        print("Your available balance",amount)
    elif ch==3:
        print("Your available balance",amount)
    else:
        print("Wrong Input")
else:
    print("Invalid Pin number")
    
    
    

```

    Enter the pin Number:1234
    1.Deposite
    2.Withdrwal
    3.BalanceEnquiry
    Enter Your Choice1
    Enter the Deposite amount2000
    Your available balance 12000
    
