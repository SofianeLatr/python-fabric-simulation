# python-fabric-simulation
Old 2024 pygame fabric/cloth simulation project 

The idea is simple (nodeBeam system). Create a grid of nodes where each node is connected to 4 other points in each side with a beam, each node exprience gravity, friction, a collision check with the ground, bouncing reaction and corection on each loop update, this we result in the movement of nodes and beams get either stretched or squished. So we run a process where beam length get devived with a factor to keep the original beam length. 2 nodes or more coordinates are kept static so the grid doesn't fall to the ground.

I added curser dragging and cutting later. Press LEFT click to drag the mesh from a node, and LEFT click to cut beams.

if you exprience stuttering you can decrease the number of nodes on xpoints_num and ypoints_num

<img width="392" height="229" alt="image" src="https://github.com/user-attachments/assets/231b6f6b-8363-4e56-980c-70cbe330dced" />
