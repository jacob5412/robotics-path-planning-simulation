# Path Planning Simulator

Path planning simulator for the project component of CSE3011: Robotics and its applications at Vellore Institute of Technology, Vellore.

## Javascript Simulator
A simple extension of the simulator has been implemented in JavaScript for ease of viewing in web browsers. The JavaScript version contains the following algorithms:
<ol>
<li>Breadth First Search</li>
<li>Depth First Search</li>
<li>Dijkstra's Algorithm</li>
<li>Greedy Best First Search</li>
<li>A-Star Algorithm</li>
<li>Rapidly Exploring Random Trees (RRT)</li>
<li>RRT-Connect</li>
<li>RRT-Star</li>
</ol>

To use the simulator, clone the repository to your computer and launch index.html which contains the web interface. The source file is located in the scripts folder. Upon loading, the site interface looks as follows, showing the algorithms on top with a textbox for statistics:

<p align="center">
  <img src= docs/images/interface.png width = 400px>
  <img src= docs/images/bfs.png width = 400px>
</p>

The respective planners can be invoked by clicking on the appropriate buttons. The textbox shows relevant statistics like the queued nodes, planner name, start and goal, when the planner is running. The preview of BFS, A*, and RRT-Connect is shown below

<p align="center">

  <img src= docs/images/astar.png width = 400px>
  <img src= docs/images/rrtconnect.png width = 400px>
</p>


The start and goal nodes can be changed by modifying the URL as follows:

`../index.html?q_init=[3,3]?q_goal=[4.5,4.5]`


## Credits
Original Project is available at [github.com/sahibdhanjal](https://github.com/sahibdhanjal/Path-Planning-Simulator). Special thanks to the developers of the original project.