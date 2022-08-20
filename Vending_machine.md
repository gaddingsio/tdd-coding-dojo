# Vending machine

In this scenario you should write a function that returns the change in coins a customer gets back from a vending machine.

Example:

A customer buys an item that costs 65 Cents and pays with a 2 € coin (here represented as 200 Cents). The change obviously will be 1,35 € (or 135 Cents). 
But since there is no 135 Cent coin, the machine would return 1 € (100 Cents) + 20 Cents + 10 Cents + 5 Cents.

So a method *"calculateChange(int payable, int paid)"* is needed. 

Where payable is the total amount the customers desired item costs. And paid is the amount of cash the customer put into the machine.

It should return an array of coins, so the vending machine can dispense the change to the customer.

So from the example above: 

calculateChange(65, 200) -> returns: [100, 20, 10, 5]

**Remember to start with baby steps and a failing test before adding any real code!**
