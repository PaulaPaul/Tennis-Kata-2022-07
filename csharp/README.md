# Tennis Society Project

Imagine you work for a consultancy, and one of your colleagues has done a small project for the Tennis Society. The contract is for 10 hours billable work, and your colleague has spent 8.5 hours working on it. It’s believed your colleague has completed the work, and the tests all pass.

Your colleague was unexpectedly called out of the country for a family matter and is not available for handoff. There are three different implementations of the scoring engine logic but your colleage did not leave notes on which should be given to the customer as the solution. Your boss has asked you to take over and spend an hour or so on the code to finalize the solution and bill the client for the full 10 hours. She instructs you select the solution, tidy up the code a little, and provide some feedback on the existing code. You should also prepare to talk about the value of any refactoring work, over and above the extra billable hours, and the value of other potential approaches to the problem that could be discussed with the Tennis Society.

You’ve also been asked to pair with another colleague who has not done work in the coding language you will be working in, but who has experience in another coding language, in an effort to help cross-train your team.

## Why?

The Tennis Society is feeling pressure to modernize and standardize their digital scoring system.  The digitizing process is new and scary to a long standing and well-known institute, and they are giving small pieces of work to different consultancies to get familiar with the process, and to determine which consultancy provides the best value and matches the Tennis Society’s working style.  This is how we ended up with 10 billable hours of senior engineering work.

The goal is to provide a scalable, reliable, accurate and trustworthy scoring system for veterans to the game, and also give newcomers to the game an easy and consistent way to understand the quirky nature of the scoring system.

The Tennis Society has members around the world, and the scoring engine is expected to eventually support thousands of concurrent players through the new digital scoring system.

## What

Our company won a 10-hour project to build out the backend scorekeeping engine logic.  The Tennis Society has provided the technical definition of the interfaces they want us to implement. Here are the requirements provided for this MVP:

- A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
- The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as “Love”, “Fifteen”, “Thirty”, and “Forty” respectively.
- If at least three points have been scored by each player, and the scores are equal, the score is “Deuce”.
- If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is “Advantage” for the player in the lead.
- We only need to report the score for the current game. Sets and Matches are out of scope.
