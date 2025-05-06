# Rule-Based-Catan-Players
This project implements and evaluates multiple rule-based AI players for the board game Settlers of Catan,
using the Tabletop Games (TAG) Framework developed by GAIGResearch.
Each player adopts a different strategy—such as expansion or resource monopoly—and their performances 
are compared through automated simulations.

-- File Overview --
Inside TabletopGames-master\TabletopGames-master\src\main\java\players\rulePlayer
RulePlayer1.java	     Expansion Focused Player
RulePlayer2.java	     Monopoly and Port Focused Player
RulePlayerHelper.java	 Contains utility methods shared between both rule-based players
CatanBoard.drawio	     Annotated diagram of the Settlers of Catan board for reference

-- How to Run the Players --
To run your custom players against specific opponents in the TAG framework:
1. Locate the Game.java file: TabletopGames-master\TabletopGames-master\src\main\java\core
2. Scroll to the bottom of the file (around lines 889–908) and comment in/out the AI players you want to use in the game
3. Change the number of games to simulate: On line 920, modify the value of nRepetitions to the desired number of matches
4. Run the Game.java file to start the simulation
