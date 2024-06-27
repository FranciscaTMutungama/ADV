import time

def introduction():
    print("Welcome to the Adventure Game!")
    print("You find yourself standing in front of a mysterious cave entrance.")
    print("Do you want to enter the cave? (yes/no)")
    choice = input().lower()
    if choice == "yes":
        cave_entrance()
    else:
        print("You decide not to enter the cave. The adventure ends here.")

def cave_entrance():
    print("\nYou enter the dark cave and see two tunnels.")
    print("One on the left, and one on the right.")
    print("Which tunnel do you choose? (left/right)")
    choice = input().lower()
    if choice == "left":
        left_tunnel()
    elif choice == "right":
        right_tunnel()
    else:
        print("Invalid choice. Try again.")
        cave_entrance()

def left_tunnel():
    print("\nYou venture into the left tunnel and discover a treasure chest!")
    print("Do you want to open it? (yes/no)")
    choice = input().lower()
    if choice == "yes":
        print("Congratulations! You found a pile of gold coins. You win!")
    elif choice == "no":
        print("You decide not to open the chest and return to the cave entrance.")
        cave_entrance()
    else:
        print("Invalid choice. Try again.")
        left_tunnel()

def right_tunnel():
    print("\nYou head into the right tunnel and encounter a fearsome dragon!")
    print("What will you do? (fight/run)")
    choice = input().lower()
    if choice == "fight":
        print("You try to fight the dragon, but it's too powerful. You are defeated. Game over!")
    elif choice == "run":
        print("You run away from the dragon and return to the cave entrance.")
        cave_entrance()
    else:
        print("Invalid choice. Try again.")
        right_tunnel()

def main():
    introduction()
    print("\nThanks for playing!")

if __name__ == "__main__":
    main()
