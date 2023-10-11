# Magic-Eight-Ball
In this project, we will build a Magic Eight Ball using control flow in JavaScript. The user will be able to input a question, then our program will output a random fortune.

# Tasks
#1 In the first line of the program, define a variable called userName that is set to an empty string.
If the user wants, they can enter their name in between the quotation marks.

#2 Below this variable, create a ternary expression that decides what to do if the user enters a name or not. If the user enters a name — like 'Jane' — use string interpolation to log Hello, Jane! to the console. Otherwise, simply log Hello!.

#3 Create a variable named userQuestion. The value of the variable should be a string that is the question the user wants to ask the Magic Eight Ball.

#4 Write a console.log() for the userQuestion, stating what was asked. You can include the user’s name in the console.log() statement, if you wish!

#5 We need to generate a random number between 0 and 7.

Create another variable, and name it randomNumber. Set it equal to this expression, which uses two methods (Math.floor() and Math.random()) from the Math library.

#6 Create one more variable named eightBall, and set it equal to an empty string. We will save a value to this variable in the next steps, depending on the value of randomNumber.

#7 We need to create a control flow that takes in the randomNumber we made in step 5, and then assigns eightBall to a reply that a Magic Eight Ball would return. Think about utilizing if/else or switch statements. Here are 8 Magic Eight Ball phrases that we’d like to save to the variable eightBall:

'It is certain'
'It is decidedly so'
'Reply hazy try again'
'Cannot predict now'
'Do not count on it'
'My sources say no'
'Outlook not so good'
'Signs point to yes'
If the randomNumber is 0, then save an answer to the eightBall variable; if randomNumber is 1, then save the next answer, and so on. If you’re feeling creative, make your own responses!

#8 Write a console.log() to print the Magic Eight Ball’s answer, the value of the eightBall variable.
