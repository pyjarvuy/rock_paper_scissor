# rock_paper_scissor
print("you have three option(rock,paper,scissor)")
while True:
 player1=input("Enter your option(rock,paper,scissor): ")
 player2=input("Enter your option(rock,paper,scissor): ")
 if player1==player2:
  print("game is tie")
 elif(player1== "rock"):
    if(player2== "paper"):
     print("player 2 wins")
    else:
     print("player 1 wins")
 elif(player1=="paper"):
     if(player2== "scissor"):
      print("player 2 win")
     else:
      print("player 1 wins")
 elif(player1=="scissor"):
     if(player2=="rock"):
      print("player 2 wins")          
     else:
      print("player 1 wins")
 else:
     print("out of the option")
 command=input("if you want to exit put exit for continue press enter: ")
 if command=="exit":
     break
