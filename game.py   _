import random

player_score = 0
computer_score = 0
response = ""
completed = False

player_choices = ["paper","rock","scissors","paper","paper","rock","rock","scissors","scissors"]
computer_choices = ["paper","rock","scissors","rock","scissors","paper","scissors","rock","paper"]
result = ["tie","tie","tie","win","lose","lose","win","lose","win"]

while response != "y":

    completed = False

    player_choice = str(input("Enter your choice: "))
    print()

    random_number = random.randint(1,3)
    if random_number == 1:
        computer_choice = "rock"
    elif random_number == 2:
        computer_choice = "paper"
    else:
        computer_choice = "scissors"
    
    print(f"you chose {player_choice}, computer chose {computer_choice}")

    for x in range(len(player_choices)):
        if player_choices[x] == player_choice:
            if computer_choices[x] == computer_choice:
                completed = True
                if result[x] == "win":
                    print("you won!")
                    player_score += 1
                elif result[x] == "lose":
                    print("computer won")
                    computer_score += 1
                else:
                    print("it was a tie")

    if completed == False:
        print(f"you chose {player_choice}, what even is that???")

    print()
    print(f"player score: {player_score} computer score: {computer_score}")
    print()
    response = str(input("enter [Y] if you want to quit: "))
    print()
    print()
    print()
    print()