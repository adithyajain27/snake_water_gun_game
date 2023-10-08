#snake water gun
# using if else conditions
# conditions 

import random
# import string
def computer_choice():
    choices = ["snake"," water","gun"] 
    computer_choice = random.choice(choices)
    return computer_choice

def user_choice():
    choices = ["snake"," water","gun"] 
    print(choices)
    user_input = input("enter the choice you want in snake, water, gun : \t")
    if user_input in choices:
      return user_input.lower()
    else:
      print("please select the correct choice ")
    

def snake_water_gun(user, computer):
  
    if user == computer:
      return "It\'s a tie"

    elif user == "snake":
      return "you win" if computer == "water" else "computer win\'s"

    elif user == 'water':
        return "You win!" if computer== 'gun' else "Computer wins!"
      
    elif user == 'gun':
        return "You win!" if computer == 'snake' else "Computer wins!"

def main():
  print("HELLO WELCOME TO THE SNAKE, WATER,  GUN GAME")
  while True:
    user = user_choice()
    computer = computer_choice()

    print(f"the computer choice is {computer} and user choice is {user}")

    result = snake_water_gun(user, computer)
    print(result)

    play_again = input("you want to continue then enter \'yes\' else \'no\' :\t ")
    if play_again.lower() != 'yes':
      print("Thank you for playing the game")
      break
    

if __name__ == "__main__":
  main()




