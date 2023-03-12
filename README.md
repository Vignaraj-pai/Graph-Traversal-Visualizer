# Graph Traversal Visualizer
This is a Python project that allows you to visualize the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms for graph traversal. The project is built using the following libraries:

- NetworkX for creating and manipulating graph structures
- Matplotlib for visualizing the graphs and search algorithms

The project includes two main Python scripts:

- `dfs.py`: This script implements the DFS algorithm and generates a sequence of images that visualize the search process.
- `bfs.py`: This script implements the BFS algorithm and generates a sequence of images that visualize the search process.
The images generated by each script can be combined to create an animation that shows the algorithm in action.

## Usage
To use the visualizer, you need to have Python 3 installed on your machine, as well as the NetworkX and Matplotlib libraries. You can install these libraries using requirements.txt:

`pip install -r requirements.txt`

To visualize the DFS algorithm, run the following command:

`python dfs_visualizer.py`

To visualize the BFS algorithm, run the following command:

`python bfs_visualizer.py`

Both scripts will prompt you to enter the number of nodes in the graph. Once you enter this value, the script will generate a random graph with that many nodes and edges. The search algorithm will then be applied to the graph, and a sequence of images will be generated that show the search process step by step.

## Visualization
The images generated by the scripts are saved in the dfs_images and bfs_images folders, respectively. Each image shows the current state of the search algorithm, with nodes and edges colored to indicate their status (visited, unvisited, etc.). The images are numbered in sequence, starting from 0.
The images are then converted into a gif for the traversal animation using the `imageio` library.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code as long as you include the license file and attribute the original authors.
