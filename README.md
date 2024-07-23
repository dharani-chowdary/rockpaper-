import random
 
comp_wins = 0
player_wins = 0

def
Choose_Option():
    user_choice = input("Choose Rock, Paper or Scissors: ")
    if user_choice in ["rock", "r"]:
        user_choice = "r"
    elif user_choice in ["paper" , "p"]:
        user_choice = "p"
    elif uselif comp_choice == "p":
            print("computer choosed paper you win")
            player_wins += 1
        elif comp_choice == "s":
            print("tied")

    print("")
    print("Player wins: " + str(player_wins))
    print("Computer wins: " + str(comp_wins))
    print("")

    user_choice = input("again? (y/n) ")
    if user_choice in ["y"]:
        pass
    elif user_choice in ["n"]:
        break
    else:
        breakr_choice in ["scissor" , "s"]:
        user_choice = "s"
    else:
         print ("not found")
         Choose_Option()
    return user_choice
    
def Computer_Option():
    comp_choice = random.randint(1,3)
    if comp_choice == 1:
        comp_choice = "r"
    elif comp_choice == 2:
        comp_choice = "p"
    else:
        comp_choice = "s"
    return comp_choice

while True:
    print("")
    user_choice = Choose_Option()
    comp_choice = Computer_Option()
    print("")

    if user_choice == "r":
        if comp_choice == "r":
            print("tied")
        elif comp_choice == "p":
            print("computer choosed paper you loose")
            comp_wins += 1
        elif comp_choice == "s":
            print("computer choosed scissors you win")
            player_wins += 1
            
    elif user_choice == "p":
        if comp_choice == "r":
            print("computer choosed rock you win")
            player_wins += 1
        elif comp_choice == "p":
            print("computer choosed paper tied")
        elif comp_choice == "s":
            print("computer choosed scissors you lose")
            comp_wins += 1

    elif user_choice == "s":
        if comp_choice == "r":
            print("computer choosed rock you loose")
            comp_wins += 1
        e
            
