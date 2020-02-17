# BallGame
A.	Design a class BallGame that has the following instance variables and properties:
1.	Name of first team and name of second team
2.	Number of players in each team (one single variable)
3.	Number of substitutes (one single variable)
4.	Score of first and second team
- Provide a default constructor that sets names of teams to “Unknown”, number of players, substitutes and scores to 0.
- Provide a constructor that accepts specific values for each of the private members.
- Provide accessors for each of the members 
- Provide mutators for each of the private members
- Provide a method TeamAScored and TeamBScored that increases the score of the appropriate team by a specified value (i.e TeamAScored accepts an integer).
- A method display that displays all attributes of an object
- Povide a method Equal that accepts an object BallGame and returns true if the object is equal to current object and false otherwise.
- Provide a method WhoIsWinning that returns the name of the winning team or “Draw” if both have same score.
B. Derive a class SoccerGame that has in addition the following: 
1.	Principal Referee’s name
2.	Number of players substituted
- Provide a default constructor that sets team names and referee’s name to “unknown”, number of payers to 11, number of substitutes to 5 and the score of each team as well as number of players substituted to 0.
- Provide a constructor that accepts the names of the teams and the referee’s name.
- Provide accessors and mutators for referee’s name and number of players substituted
- Override the method display to display all private attributes.
- Override the method Equal to compare two SoccerGames
- Override  TeamAScored and TeamBScored that accepts an integer to increase the score of the appropriate team by 1 even if the number specified is larger than 1.
- Overload TeamAScored and TeamBScored (no input parameter) to increase the score of the appropriate team by 1.
- Provide a method SubstitutionA, SubstitutionB that increases the number of players substituted for the appropriate team by 1 if it is less than 3, otherwise it displays “No more substitutions allowed”.
C. Write a class tester (main) where you test every method and constructor of both classes. Print the output of your program. 

