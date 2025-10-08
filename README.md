# Rock-paper-scissors-game
mport random
hand="rock"
guess=0
attempts=0
while guess!=hand:
    guess=input("guessing: ")
    attempts+=1
    if hand=="rock" and guess=="paper" or guess=="rock" or hand=="paper" and guess=="scissor":
      print("you win")
      print(f"congratulations you try in attempts :{attempts}")
      break
    elif hand==guess:
     print("tie")
    elif guess!="paper" or guess!="scissor" or hand!="scissor":
        print("invalid choice")
    else:
     print("you lose")

