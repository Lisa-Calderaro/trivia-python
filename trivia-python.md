python trivia game
def bet_money():
    bet = int(input("How much would you like to start your bet?     "))
        while bet < 0 or bet >+ 1000:
            print("That is an incorrect choice. Please enter a bet between 1 and 1000:    ")
            bet = int(input("How much would you like to bet?:     "))
            print("You placed a bet of:   ",bet, "dollars.")
            print("\n")
            return bet

#      Start Game
print("Hello! Let's play a simple trivia betting game.")
print("\n")
print("You will have 1000 dollars to start. Good Luck!")
#      input prompts user to enter an amount to bet

money = 1000

#     input prompts user it's first question
bet = bet_money()
print("Here's your first question: What is the elevation of Mt. Everest?")
print("a = 29,029 ft")
print("b = 29,002 ft")
print("c = 28,848 ft")

#     input prompte user to answer first question
Q1 = input("Please enter your choice:   ")
while Q1 != "a" and Q1 != "b" and Q1 != "c":
    print("Please enter your choice. (a, b, or c):   ")
Q1 = input("Please enter your choice:    ")
    print("Your answer is:   ", Q1)

if Q1 == "b":
    money += bet
        print("Congratulations! You now have:    ",money,"dollars")
    else:
    money -= bet
        print("Oops!, that is not the expected answer. Your balance is now:     ",money,   "\n")

#     input would you like to continue
cont = "Would you like to continue?"
Q1 = input(cont)
while Q1 != "y" and Q1 != "n":
    print(cont + "(y, n):    ")
Q1 = input("Please enter you decision:   ")

if Q1 == "n":
    print("Game over!!! Your final total is:    ", + money)
    else:

#     input prompts user it's second question
    bet = bet_money()
        print("Here's your second question: In what year was Mount Fuji, Japan's last confirmed eruption?")
            print("a = 1698")
            print("b = 1707")
            print("c = 1716")

#     input prompts user to answer second question
Q1 = input("Please enter your choice:   ")
while Q1 != "a" and Q1 != "b" and Q1 != "c":
    print("Please enter your choice.  (a, b, or c):    ")
    Q1 = input("Please enter your choice:   ")
        print("Your answer is:    ", Q1)

if Q1 == "a":
    money += bet
        print("Congratulatons! Your are doing very well! You now have:     ", money, "dollars")
    else:
        money -= bet
            print(Oops!, that is not the expected answer. Your new balance is:     ", money, "\n")

# input prompts if user would like to continue

cont = Would you  like to continue with another question?"
Q1 = input(cont)
while Q1 != "y" and Q1 != "n":
    print(cont + "(y,  n):    ")
    Q1 = input("Please enter your decision:     ")

if Q1 == "n":
    print (Game over!!! Your grand total is:     ", money,  "\n")
else:

#     input prompts user it's third question
        bet = bet_money()
        print("Here's your third and final trivia question: On what coast of Italy sits the remains of Mount Vesuvius?")
            print ("a = West Coast")
            print("b = Southern Coast")
            print("c = East Coast")

#     input prompts user to answer third question
Q1 = input("Please enter your selection:   ")
while Q1 != "a" and Q1 != "b" and Q1 != "c"
    print("Please enter your selection.  (a, b, or c):   ")
    Q1 = input("Please enter your selection:  ")
        print("Your answer is:     ", Q1)

if Q1 == "a":
    money += bet
    print("Congratulations You're a WINNER!!! Your grand total winnings are:     ", money,  "dollars")
else:
    money -= bet
        print("Oops!, that is not the correct answer. Your balance is now:     ", money,  "\n")

#     input prompts user there are no more trivia questions
    print("We are now finished with our trivia questions")

if Q1 == "n":
    print("Game over !!! Your grand total is:     ", money,  "\n")
        print("Thank you for stopping by to play trivia today. Stop by soon and try your skill with Trivia of the Century and win BIG!")
