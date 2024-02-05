import random
print("BOT:I AM THINKING OF NUMBER---:")
SecretNumber = random.randint(1,101)
attempts=0
while True:
    Guess =int (input("GUESS A NUMBER:"))
    attempts+=1
    if Guess == SecretNumber:
        print(f"congratulations! u have guess the number in{attempts}attempts")
        break
    elif Guess < SecretNumber:
        print ("BOT: TRY FOR A HIGHER NUMBER!")
    else:
        print("BOT: TRY FOR A LOWER NUMBER!")

