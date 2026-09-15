# ALE_Pacman_v5_stage1_perfect-clear_DDQN

**Type of RL agent**: DDQN

**Agent performance**: Stage 1 of ALE_Pacman_v5 is perfectly cleared by DDQN with around 98.5% chance. The trained weights of the NN were uploaded as hS files. The video below shows the agent performing.


https://github.com/user-attachments/assets/27248e4d-8e21-4af6-96cc-46e4c954c14b


**Raw input**: RAM

**Input processing**: Raw RAM input was processed to represent a graph structure for distances and paths between objects. Related coordinates and node-edge information were uploaded as npy files. 

**Key structure**: A smooth transition using tanh function is applied to treat embeddings for normal mode and scary mode differently. Structural attention is applied. For example, for ghosts, attention is used to focus on the most important ghost. Also, among objects such as pellets, power pills, and ghosts, attention focuses on the most important object. 







