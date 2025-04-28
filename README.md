# csc401-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [CSC401 Assignment 6 Solved](https://www.ankitcodinghub.com/product/csc401-assignment-6-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118051&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC401  Assignment 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Reading

Read Chapter 7 in Introduction to Computing using Python: An Application Development Focus, Second Edition by Ljubomir Perković.

Logistics

You need to do this assignment on a computer which has Python 3 installed on it. Python 3.8.5 download page can be found here.

A submission that includes code which does not run will not get any points for the part unless specifically documented reason of the error.

Assignment

1. (40pt) Rock, paper, scissors

Rocker paper scissors is a very simple hand game. If you don’t know to rule, refer to the Wikipedia page https://en.wikipedia.org/wiki/Rock_paper_scissors.

For this problem, you will implement the game in the way you like. The player will play against the computer in a fair way. Here are some requirements for the game.

• There should be multiple rounds. You can use a parameter to choose how many rounds or let the player decide when to end.

• Result and score should be displayed at end of each round.

• It must be a fair game. Player cannot know what computer chooses and computer cannot know what player chooses.

• The game should recover gracefully from in valid input typed by the player

Please document your implementation in the docstring so people will know how to play your game when they call help() on your function.

2. (60pt) ATM Machine

You are to simulate a very simple ATM machine that has a full keyboard. An account owner (user) should be able to enter their pin number and select from a menu of transactions: Deposit, Withdraw, Balance, and Quit. You are to assume that the user has only one account on which these transactions can be performed. This account is associated with the user’s pin number.

The ATM should properly and regularly communicate with the user. The ATM should get information on current account from a file (accounts.csv). This file is posted with the assignment in the submission folder. Each line of the file contains a 4-digit code (pin), first name, last name, and the account balance. Contents of accounts.csv file follows:

Steps

1. (10pts) Write a function startUp(filename) that takes as parameter a filename that contains the account owner (user) information and current account balance.

• Initialize the dictionary in the function. All variables in this program must be local variables.

• If the filename is invalid, hander the error, print ‘Cannot get to the file’ and return None.

• If the filename is valid, read the file and store each line in the dictionary.

i. The key is the 4-digit code (pin), and the value is a list with the user first name, last name and balance. Balance is a float. Do an explicit conversion to float on that list item. ii. The function returns the dictionary if the file was successfully read and the dictionary successfully filled with the file data; if the file is not successfully opened/read, return None.

2. (5pts) Write a function verifyPin(d) that takes as parameter the dictionary.

• Prompt the user to enter a pin number.

• If the pin is valid, that is, it is 4-digits and is in the dictionary, return pin and name where pin is the dictionary key and name is the user’s first name. If the pin is invalid, print ‘Incorrect pin’ and return

(None, None).

3. (5pts) Write a function menu(name) that takes as parameter the user’s first name, displays the user’s name and the menu options:

• D: Deposit

• W: Withdraw

• B: Balance

• Q: Quit

If the user enters a value that is not D, W, B, Q, then print the message ‘Valid choices are D, W, B, Q, try again’ and display the menu options again. When a valid number is entered, the function should return the letter of the chosen option.

4. (10pts) Write a function getAmount() that takes no parameters.

• Inside a loop, prompt the user for an amount to be deposited or withdrawn; at this point it does not matter which it is. The amount must be converted to float. If the amount is negative, print ‘Negative amount. Please try again’.

• If user gives an invalid input, handle the error and print ‘Invalid amount. Use digits only’.

• Stay in the loop until a valid number is entered and return that amount.

5. (5pts) Write a function deposit(pin, d) that takes as parameters the user’s pin number and the dictionary. The function calls getAmount(), calculates the new balance, updates the dictionary and prints a message of success. The function does not return a value.

6. (10pts) Write a function withdraw(pin, d) that takes as parameters the user’s pin number and the dictionary. The function calls getAmount(). If the amount to be withdrawn is greater than the balance print ‘Insufficient

funds to complete the transaction’. The user should be prompted to enter a new amount, until the amount entered is less than or equal to the balance. The function uses the balance in the dictionary to calculate the new balance. The balance is updated in the dictionary. This function does not return a value.

7. (5pts) Write a function balance(pin, d) that takes as parameters the user’s pin number and dictionary and returns the user’s balance from the dictionary.

8. (5pts) Write a function quit(pin, d) that takes as parameters the user’s pin number and dictionary. The user is prompted as to whether or not she wishes to leave the transaction. If she does, then the function returns the user’s first and last name. If she does want to leave the application, then return (None, None).

Submission

Submit the assignment using Assignment 6 folder. Save each program to a separate file labeled as YourName_assign6_1.py and YourName_assign6_2.py.
