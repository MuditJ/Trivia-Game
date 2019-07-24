
PROJECT TITLE: PSYCH - A TRIVIA GAME

PROJECT DESCRIPTION:
Psych is a multi-player trivia game where the players supply the options to different questions.
The game begins by giving the players a question, to which thyere supposed to give an answer. 
Once all the answers are taken, The question, with the correct answer+the answers that the players gave would be given to each player. Now it's up to the player to decide which one of these is the correct answer, and choose one.

The aim of the game is:
1) For each question, give a smart answer that seems like the correct answer, so that the other players select it, fetching you points.
2) To be able to select the right answer from the bunch of answer given to you.

If you select an answer which is not correct and thus, provided by one of the other
players, you are said to be 'psyched', hence giving some points to the person who submitted this answer in the beginning.

There are points alloted for getting the answer right and for every player you psych. In our implementation
of the game, we have set it to +10 points for selecting the right answer, +5 for every player you psych(every other
player who selected the wrong answer you provided, thinking that it was the correct answer) and -5 for
getting psyched (selecting the wrong option). 

The game continues for as many rounds as specified in the program before starting the game. At the end of
the game, the game displays who the winner is.

In our implementation, we have by default, set the game to have 2 players(2 clients) and there is one
server program process. We have also set the game to be played for a single round.

