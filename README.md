Todos:
    Step 1 - Add the rFlutter Alert package as a dependency here and use "Packages get"

    Step 2 - Import the rFlutter_Alert package here.

    Step 3 Part A - Create a method called isFinished() here that checks to see if we have reached
                    the last question. It should return (have an output) true if we've reached the
                    last question and it should return false if we're not there yet.
    Step 3 Part B - Use a print statement to check that isFinished is returning true when you are
                    indeed at the end of the quiz and when a restart should happen.

    Step 4 - Use IF/ELSE to check if we've reached the end of the quiz. If so, on the next line,
             you can also use if (quizBrain.isFinished()) {}, it does the same thing.
    Step 4 Part A - show an alert using rFlutter_alert
    Step 4 part B - Create a reset() method here that sets the questionNumber back to 0.
    Step 4 Part C - reset the questionNumber
    Step 4 Part D - empty out the scoreKeeper

    Step 5 - If we've not reached the end, ELSE do the answer checking steps below
