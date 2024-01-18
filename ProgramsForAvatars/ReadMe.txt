To get things running on Linux of Mac, do the following:

A -- Run the Bots

- Navigate in a terminal to the GeneSimulation_cpp folder
- Compile the code: g++ main.cpp -o jhgsim
- Run the code: ./jhgsim play ../ResultsSaved/theGenerations 70 1 49 10 30 best_agents equal 0 nondeterministic humanConfig

Notes: 
- If you want to change the length of the game, chance the 30 above to a different number of rounds
- If you want to change the number of agents in the game, change the 10 to the number you want
- If you want to change the behavior of the agents, change the 49 to a number between 0 and 49 or change best_agents to rnd_agents


B -- Start the Human Player

- Navigate in a different terimanl to the Human folder
- Compile the code: javac *.java
- Run the code: java Human

You can player the game through the GUI.  The GUI buttons may be off a little bit.  Different operating systems do different things with the GUI display.  I can try to fix these on your machine if you are having problems with them.


C -- Once you have these programs running, the game is being played.  You need to create a separate program Dart/Flutter that reads from the file State/state.txt.  This file contains information about the game that is relevant to the Avatar