# Dice-Rolling-Simulator-Python
import random
min = 1
max = 6

roll_again = "yes"

while roll_again == "yes" or roll_again == "y":
    print "Rolling the dice..."
    print "The value is...."
    print random.randint(min, max)

    roll_again = raw_input("Roll the dice again?")
