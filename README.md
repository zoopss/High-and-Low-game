# High-and-Low-game
print "*****Welcome to | -- HIGH /LOW -- | game*****" # it is just intro duction to the game
import random
stat = 0
x = random.randint(0,100)
a = int(raw_input("Enter your number:")) 
while stat != 1 :
	if a < x:
    		print "Too Low"           # it will print because the number you have entered is smaller than the random number
    		a = int(raw_input("Enter your number:"))
	elif a > x:
    		print "Too High"                 # it is shown becaus the number you have entered is too large than the random number
    		a = int(raw_input("Enter your number:"))
	else:
		stat = 1   

print'  \    /   |*****|   |     |   \            /   ----|----  |\    | '   # It is shown as the number  entered is exact to the random number
print'   \  /    |     |   |     |    \          /        |      | \   | '
print'    \/     |     |   |     |     \        /         |      |  \  | '
print'    /      |     |   |     |      \  /\  /          |      |   \ | '
print'   /       |_____|   |_____|       \/  \/       ____|____  |    \| ' 
