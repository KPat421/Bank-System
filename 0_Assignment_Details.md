# Bank-System

You are a back-end developer and you are required to design s system for a Bank. Your application should be able to handle new customer bank account requests. In addition, it should be mentioned that, a bank is identified by its name, license number, and it contains many bank accounts and many bank customers. A bank account can be either a checking or a savings account. Both checking and savings accounts share the following properties:
1) Bank Customer name
2) Social security number
3) Account Number
4) Balance
5) Credit card number
6) PIN-code
7) deposit()
8) withdraw()
9) checkBalance()
10) showInfo()
11) showMenu()

Below is the description of the all required methods:
1) deposit(): It should enable the user to deposit a certain amount of money. Accordingly, it should increase the account balance by that amount.
2) withdraw(): It should enable the user to withdraw a certain amount of money. Accordingly, it should decrease the account balance by that amount.
3) checkBalance(): It should display the balance in the account
4) Showinfo(): It should reveal all the relevant information, like customer’s name, type of account, and balance.
5) ShowMenu(): This method displays a welcome message and display for the users all possible operations. It should give the user the option to:
 Press A for deposit
 Press B for withdraw
 Press C for check balance
 Press D for show info

Based on that, it will wait for the user’s selection, and call the appropriate method. For example, if the user entered A, for deposit, the user should be asked about the amount of the deposit, call the deposit() method and add the deposit amount to the account’s
balance. Similarly, if the user’s selection is D, it should call the showinfo() method and display the relevant information.

In addition, each bank customer can have multiple bank accounts either checking accounts or saving account. Each bank customer is identified by name, social security number, and the associated bank accounts.

Finally, your application should be able to handle adding new account. In other words, you should add a method called addAccount() to add a new account. You should be able to know where to add this method, i.e., in which class this method should be added?
