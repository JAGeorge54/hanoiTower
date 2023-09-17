# hanoiTower
Module 10 Codio Assignment
Hanoi Tower
Now that you’re familiar with the Hanoi Tower problem, you can explore how to customize its algorithm to add more disks.
The starter code for this activity includes the solution to the Hanoi Tower problem. Currently, this solution works for five disks only.
You can use the application by pressing the Make Move button. The first press will load the Hanoi Tower. Every button press after that iterates through solving the Hanoi Tower. When the Hanoi Tower is solved, on the last button press, you will receive an alert stating Tower is Finished.
Your task in this activity is to edit this solution to add a custom number of disks to the tower.
You can accomplish this task by doing the following:
Add an input box with the ID: numDisk under the make move button in the index.html file. This input box will contain the custom number of disks.
Use the input from that box to adjust the Hanoi Tower algorithm to account for all the disks.
Hint: In the tower.js file, find the makeMove function. Then think about how to retrieve the value that the user typed in the <input>. Finally, consider where in the function to set the nDisks variable to the user’s input value.