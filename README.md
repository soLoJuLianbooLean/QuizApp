# QuizApp

This is one of the projects I created while studying the 'iOS & Swift - The Complete iOS App Development Bootcamp' course on Udemy:
https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/.

This is a quiz app with an array of questions and corresponding respondes. 
If the user answer == the actual answer, the button background changes to green, or red if incorrect. This gives the user feedback on their answer.

Included a timer to reset the button colors to clear after .2 seconds. 

Created a function called 'updateUI' to change the question that the user is reading.
Varable 'questionNumber' corresponds to the question that the user is reading. 'questionNumber' += 1 moves onto the next question after the 'updateUI' function. 
