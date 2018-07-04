# doYouEvenCode
  JavaScript Quiz App<br>
This is the project on wich me, and my other 3 coleagues have worked on during the JavaScript course, here is a sketch of what we used to get it up in this state :<br>
-at start we have 2 forms on wich we ask for users github username, wich then is used to get the repos number of the respective user with the help of github API(used eventListener in order to send request) - https://developer.github.com/v3/?<br>
-we then purceed to the second page wich tells the user how many repos have.<br>
-folowing is the quiz itself wich is displayed as 1 question and 3 checkboxes as a choice option(answers) on each page.<br>
-we used Math.random method to randomly display the questions from a list of 100, in order not to be memorized.<br>
-we then used a "for in for" method to loop through each answer available in order to get the selected value<br>
-we also added multiple answers questions and used "else/if" conditions to check if the user has selected correct answer/s, if not the respective question will not be scored.<br>
-in order to calculate the score we've made 2 lists: one with all correct answers and an empty one wich will contain users corect answers, after that we compare the two lists and get the final score<br>
-at last we added a "Save results" button wich will save the resulst into a chart in local storage.
