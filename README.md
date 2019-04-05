# TriviaGame

Comments: I did develop psuedo code and a plan for desigining the solution
I spent a greate deal of time reviewing examples from in-class activities to better understand how objects, and jQuery functioned
Most of what I was able to get to work was based on in-class activities
I regret that I did not complete use of the timer
============================================
Basic Quiz

Instructions
* You'll create a trivia form with multiple choice or true/false options (your choice).

* The player will have a limited amount of time to finish the quiz. 

* The game ends when the time runs out. The page will reveal the number of questions that players answer correctly and incorrectly.

* Don't let the player pick more than one answer per question.

* Don't forget to include a countdown timer.

Pseudo code
   
    1. Build initial set of questions
      1.1 Create array or object with initil questions from full set

    2. Initiate play via "Play" event
      2.1 Set "Play" page
      2.2 Get any play start event 
      
      2.3 Set timer
      2.4 Set initial questions page with "Done" button
      2.5 Get any user "done" event
          2.5.1 Check for completed answers and stop if complete
                otherwise alert that answers are not complete

      2.6 decriment timer and get answers
          2.6.1 Check for completed answers and stop if complete
          2.6.2 check time and stop if out of time

      2.7 Stop 
          2.7.1 Stop timer
          2.7.2 Report results
