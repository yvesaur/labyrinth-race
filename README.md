# labyrinth-race
2D Maze Game with implemented Tremaux Algorithm for the enemy bot pathfinding.

# I. Description
This game is designed to challenge your problem-solving skills as you navigate through intricate mazes filled with twists and turns. The objective is simple: find your way through the maze and reach the end goal. But be careful, as there are obstacles and an enemy trying to finish the maze before you, waiting to halt your progress. Are you ready to take on the challenge? You vs. the computer will compete on who can reach the exit in time or who finishes first. Who will win? Who really is the smartest entity in the room?

# II. Mechanics
<ul>
  <li>A human player and a computer (AI) opponent have a task to solve the maze and race to the finish line, the first player to reach the finish line will be declared a winner.</li>
  <li>The AI that will be the opponent of the player will have difficulty with easy, normal, and hard. The player can choose what difficulty of bot they will encounter.</li>
  <li>There are three different mazes ranging from level 1 to 3, each level will have a more difficult maze than its previous level.</li>
  <li>There will have to be a certain timer to finish the maze if one of the competitors did not finish the race after the timer ends. It will automatically die.</li>
  <li>The bot will not be trained for the maze. The bot will learn in real time as the player plays.</li>
</ul>

# III. Algorithm
<h3>Tremaux's Algorithm</h3>
<ol>
  <li>Tremaux's algorithm is a maze-solving algorithm that was invented by Charles Pierre Trémaux in 1844. It is a simple and efficient algorithm that can be used to find the way out of any maze, regardless of its complexity.</li>
  <li>The algorithm works by marking the paths that have been explored. At each intersection, the algorithm chooses the path that has not been marked yet. If all of the paths have been marked, the algorithm backtracks to the previous intersection. This process continues until the exit of the maze is reached.</li>
  <li>Trémaux's algorithm is guaranteed to find the exit of any maze, but it is not guaranteed to find the shortest path. In fact, it is possible for the algorithm to find a path that is much longer than the shortest path. However, the algorithm is still a very useful tool for solving mazes.</li>
</ol>
<h3>How?</h3>
<ol>
  <li>The bot will start at the entrance of the maze.</li>
  <li>The algorithm will Choose a path that has not been marked yet.</li>
  <li>It will mark the path that has been chosen.</li>
  <li>It will follow the marked path until it reaches an intersection.</li>
  <li>The bot will repeat steps 1-4 until it reaches the exit of the maze.</li>
</ol>

# IV. How to Play?
<ol>
  <li>Download the repository and extract the file</li>
  <li>Run the LabyrinthMaze.exe file and play.</li>
</ol>
