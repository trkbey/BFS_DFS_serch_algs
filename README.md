🧩 Maze Solver
A Python script that reads a maze from a text file and solves it using Depth-First Search (DFS). The solution path is displayed in the terminal, and optionally, an image of the solved maze can be generated.

📝 Maze Format (maze.txt)
Use # for walls.

Use A for the start point.

Use B for the goal point.

Use spaces ( ) for walkable paths.

Example:

#######
#A #  #
# ### #
#   #B#
#######

🚀 How to Run
Make sure you have Python and Pillow installed.

pip install pillow
python maze.py maze.txt

🖼️ Output
Solved maze is printed in the terminal.

A .png image (maze.png) is created showing:

🔴 Red = Start

🟢 Green = Goal

🟡 Yellow = Solution path

🧱 Dark gray = Walls

🟦 Light blue = Empty space

🔶 Optional: Explored cells

🧠 Features
DFS-based maze solving

Option to switch to BFS easily

Text-based and image-based visualization

Custom maze input

🛠️ Todo / Ideas
 Implement BFS and allow choice between BFS/DFS

 Animate the solving process

 Add GUI

 Support larger mazes efficiently

