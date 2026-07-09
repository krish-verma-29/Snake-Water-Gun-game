# ==========================================
# Project : Snake Water Gun Game
# Author  : Krish Verma
# Language: Python
# ==========================================

# Import random module
import random

# Available choices
choices = ["snake", "water", "gun"]

print("=" * 40)
print("      SNAKE WATER GUN GAME")
print("=" * 40)

while True:

    # Computer selects a random choice
    computer = random.choice(choices)

    # User input
    user = input("\nEnter Snake, Water or Gun: ").lower()

    # Check valid input
    if user not in choices:
        print("Invalid Choice! Try Again.")
        continue

    print("Computer Chose:", computer)

    # Check winner
    if user == computer:
        print("Match Draw!")

    elif (user == "snake" and computer == "water") or \
         (user == "water" and computer == "gun") or \
         (user == "gun" and computer == "snake"):
        print("Congratulations! You Win.")

    else:
        print("Computer Wins!")

    # Ask to play again
    again = input("\nPlay Again? (yes/no): ").lower()

    if again != "yes":
        print("\nThanks for Playing!")
        break
