# 5010_Assignment5
This code explores a simple agent-based interaction system using randomness and mouse interaction. The goal was to create at least 100 agents whose behaviors respond dynamically to a user-controlled point.

Each agent is assigned a random value d that determines both its color and its interaction behavior. Agents with lower values appear as white points and are attracted toward the central point, while agents with higher values appear as red points and are repelled by it. Each agent also has its own distance parameter that determines how close it will move toward the center before slowing down.

The central point appears when the user clicks the mouse and follows the cursor. Clicking again reverses the interaction rules. In the normal mode, white agents are attracted and red agents are repelled. In the reversed mode, the roles switch, and the center point changes color from blue to yellow to indicate the state change.

Overall, the code successfully demonstrates controlled randomness, agent interaction, and mouse-based input. The result is a dynamic particle system that forms clusters or disperses depending on the interaction mode.

Code link:
[My_Code_LINK_HERE](https://editor.p5js.org/SanwuL/sketches/0NP-snJ8j)
