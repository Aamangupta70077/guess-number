# guess-number
n=20
i=0
while i< 10:
    a = int(input("Guess a number:"))
    if a<n:
        print("some up")
        i=i+1

    elif a>n:
        print("little down")
        i=i+1

    else:
        print("you won the game")
        i=i+1
    continue
    i = 1 + 1
print("sorry you defeat now you have no any other chance left")
