# Loops and Lists; Intro to Functions
#### Question of the Day
If you had the ability to remake a movie of your choice, what would it be? What would you do differently--who would you cast and what would you change?

### If you're up to for-loops and lists
1. Using a for-loop, start at -10 and end at 10. Print consecutive integers from -10, -9, -8, etc. and lastly print out 10. How many times does this loop iterate? **Highlighting that the stop variable is strictly less than and not less than/equal to**
2. Given an integer n (from the user), print out the square of all numbers 1 to n. **Use a for-loop.** Example: given n=3, you would print out "square of 1 is 1" then "square of 2 is 4" then "square of 3 is 9" and exit the loop.
3. Create a list of all integers, randomized values from 0-100. From this list, create two new lists: a list of all the even elements and a list of all the odd elements.
4. Given a list of integers, determine the largest element in the list. This one's interesting and difficult!

### Daniel and Alex
Create a mad-libs program using Python. Either find a mad-lib online or let them write their own mad lib. Create three lists that all have corresponding indices: 

    list1 = ["Lines that require a ____ adjective",
     "Lines that require a silly ____"]
    list2 = ["Adjective:" , "noun"]
    list3= [] #empty list to append to with the answers
    
    for i in range(0, 5, 1):
	    list3.append(input(list2[i])
	
	for i in range(len(list1)):
		print(list1[i], list3[i])

### Starting Functions
Show the pb&j sandwich function example. Highlight all the key parts: parameters, process, return statement. 

Show a simple function that takes in an x and y and returns the sum.

Create a simple function that, given a string, returns a greeting message "Hello, inputtedString!"

If it's just Inaya, have her convert some of her old loops into functions: average of numbers given a list, etc. Have her explain that code as well.
