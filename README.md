# JAVA_DEVELOPMENT
The completeion of my latest project as part of my internship with oasis infobyte
-an ATM program for representing ATM transection. In the ATM program, the user has to select an option from the options displayed on the screen. The options are related to withdraw the money, deposit the money, check the balance, and exit and an number guessing game using java development.
Key Features => ATM INTERFACE-
Following are the basic operations available in the ATM

Withdraw
Deposit
Check Balance
Exit
Approach to each Option

A. Withdraw:


Take the amount user desires to withdraw as input.
If the balance amount greater than or equal to the withdrawal amount then Perform the transaction and give the user the desired amount.
Else print Insufficient Funds message.
B. Deposit:

Take the amount user desires to deposit as input.
Add the received input from the user to balance and update its value.
balance = balance + deposit.
Print a message on screen stating deposit transaction has been successful.
C. Check Balance:

Print a message on screen showing the value of balance amount.
D. Exit:

Exit the current Transaction mode and return the user to the home page or initial screen.

NUMBER GUESSING GAME=>
The task is to write a Java program in which a user will get K trials to guess a randomly generated number. Below are the rules of the game:

If the guessed number is bigger than the actual number, the program will respond with the message that the guessed number is higher than the actual number.
If the guessed number is smaller than the actual number, the program will respond with the message that the guessed number is lower than the actual number.
If the guessed number is equal to the actual number or if the K trials are exhausted, the program will end with a suitable message.
Approach: Below are the steps:  

The approach is to generate a random number using Math.random() method in Java.
Now using a loop, take K input from the user and for each input print whether the number is smaller or larger than the actual number.
If within K trials the user guessed the number correctly, print that the user won.
Else print that he was not able to guess and then print the actual number.


