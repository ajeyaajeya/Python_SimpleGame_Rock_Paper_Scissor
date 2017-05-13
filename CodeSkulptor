# Rock-paper-scissors-lizard-Spock template
#http://www.codeskulptor.org/#user40_1RTz2unP9W_1.py
import random

# The key idea of this program is to equate the strings
# "rock", "paper", "scissors", "lizard", "Spock" to numbers
# as follows:
#
# 0 - rock
# 1 - Spock
# 2 - paper
# 3 - lizard
# 4 - scissors

# helper functions

def name_to_number(name):
        if(name == 'rock'):
            return 0
        elif(name == 'Spock'):
            return 1
        elif(name == 'paper'):
            return 2
        elif(name == 'lizard'):
            return 3
        elif(name == 'scissors'):
            return 4
#        else:
#            print "entered ", number_to_name(name), " is invalid"
    # convert name to number using if/elif/else
    # don't forget to return the result!


def number_to_name(number):
    if(number == 0):
        return 'rock'
    elif(number == 1):
        return 'Spock'
    elif(number == 2):
        return 'paper'
    elif(number == 3):
        return 'lizard'
    elif(number == 4):
        return 'scissors'
   
    # convert number to a name using if/elif/else
    # don't forget to return the result!
    

def rpsls(player_choice): 
    # print a blank line to separate consecutive games
    print "\n"
    
    # print out the message for the player's choice
    print "player chose ", player_choice
    
    # convert the player's choice to player_number using the function name_to_number()
    player_choice_num = name_to_number(player_choice)


    # compute random guess for comp_number using random.randrange()
    computer_choice_num = random.randint(0,4)
    # convert comp_number to comp_choice using the function number_to_name()
    print "Computer chose  " , number_to_name(computer_choice_num)
    # print out the message for computer's choice
    
    # compute difference of comp_number and player_number modulo five
    check = (player_choice_num - computer_choice_num ) % 5 
    if((check == 1) or (check == 2)):
        print "player wins"
    elif((check == 3) or (check == 4)):
        print "computer wins"   
    else:
        print "no winner"
    # use if/elif/else to determine winner, print winner message

    
# test your code - THESE CALLS MUST BE PRESENT IN YOUR SUBMITTED CODE
rpsls("rock")
rpsls("Spock")
rpsls("paper")
rpsls("lizard")
rpsls("scissors")

# always remember to check your completed program against the grading rubric


