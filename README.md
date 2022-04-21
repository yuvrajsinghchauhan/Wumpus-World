# Wumpus-World
The Wumpus world is a cave with 16 rooms (4×4). Each room is connected to others through
walkways (no rooms are connected diagonally). The knowledge-based agent starts from
Room[1, 1]. The cave has – some pits, a treasure and a beast named Wumpus. The Wumpus
can not move but eats the one who enters its room. If the agent enters the pit, it gets stuck
there. The goal of the agent is to take the treasure and come out of the cave. The agent is
rewarded, when the goal conditions are met. The agent is penalized, when it falls into a pit or
being eaten by the Wumpus.
Heuristics used : Early termination, Pure symbols, Unit clauses
