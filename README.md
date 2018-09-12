# Project
Dice Rolling Simulator
#This is a program to construct a dice rolling simulator
import random
min = 1
max = 6
rollAgain = "yes"
while rollAgain == "yes" or rollAgain == "y":
    print("Rolling the dices ")
    print ("The values are ")
    print (random.randint(min,max))
    rollAgain = input("Roll the dices again?")
