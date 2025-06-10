# Day-3-Treasure-Island-Game
🏴‍☠️ Treasure Island – Text Adventure Game Treasure Island is a fun, beginner-friendly Python text-based adventure game where your choices determine your fate. 🗺️  

How It Works:  
You start your journey as a treasure hunter and face a series of decisions:  
🛤️ Go left or right?  
🏞️ Swim across a lake or wait for help?  
🚪 Choose between three mysterious doors...  
    Make the wrong choice, and it's Game Over. But if you choose wisely, you’ll find the hidden treasure!  


    Skills Practiced
print() for story narration

input() for user interaction

Conditional statements (if, elif, else)

.lower() to make input handling user-friendly      
  
  
  
  #code  

print("Welcome to Treasure Island.")  
print("Your mission is to find the treasure.")  
choice1 = input("where do you want to go next?\n'Left' or 'Right' ").lower()  
if choice1 == "left":  
    choice2 = input("You have come to a lake, You wanna swim to cross the lake or want to wait on the shore?\nType 'swim' or 'wait' ").lower()  
    if choice2 == "wait":  
        choice3 = input("3 Doors appeared before you. Which one will you choose\n'Red' or 'Yellow' or 'Green' ").lower()  
        if choice3 == "red":  
            print("Your burned by fire. Game over")  
        elif choice3 == "yellow":  
            print("Treasure is found. You Win!")  
        elif choice3 == "green":  
            print("Eaten by Beasts! Game over")  
    else:  
        print("Crocodile attacked you! Game Over")  
else:  
    print("You fell into a hole! Game Over.")

    


