import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

print("1 - Rock\n2 - Paper\n3 - Scissors\n")

chs = input("What is your choice > ")

if chs == '1':
    print(rock)
elif chs == '2':
    print(paper)
elif chs == '3':
    print(scissors)

print("\nComputer is choosing now ...\n")
game_list = [rock, paper, scissors]
pc_chs = random.choice(game_list)

print(pc_chs + "\n")

if chs == '1' and pc_chs == rock:
    print("It's a draw.")

elif chs == '1' and pc_chs == paper:
    print("You lose.")

elif chs == '1' and pc_chs == scissors:
    print("You win.")

elif chs == '2' and pc_chs == paper:
    print("It's a draw.")

elif chs == '2' and pc_chs == rock:
    print("You win.")

elif chs == '2' and pc_chs == scissors:
    print("You lose.")

elif chs == '3' and pc_chs == scissors:
    print("It's a draw.")

elif chs == '3' and pc_chs == rock:
    print("You lose.")

elif chs == '3' and pc_chs == paper:
    print("You win.")

else:
    print("You typed an invalid number, you lose.")

print("\nGame Over.")
