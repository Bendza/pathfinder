# React-Matrix-Pathfinder

Welcome to the React-Matrix-Pathfinder repository! This project is a unique application that solves a matrix problem by finding a path for a moving object (MO) from start to end coordinates, while generating blocking objects (BO) on each step.

## Features
- **User Input**: The application allows users to input the size of the matrix, start and end positions, and the number of blocking objects.
- **Algorithm**: The pathfinding problem is solved using a breadth-first search algorithm, sourced from the internet. 
- **Visual Representation**: The entire process is visually represented using React, making it easy to understand and follow.
- **Performance Metrics**: The application measures the execution time and displays the number of steps taken to reach the end, providing valuable insights into the efficiency of the algorithm.
- **Blocking Objects**: The application generates blocking objects randomly within the matrix, ensuring they can't be placed on the path that the MO has already traversed.
- **Path Selection**: If a BO ends up blocking all possible paths, the application smartly reduces the number of BO by one and retries the path selection until it finds a viable path.

## Installation
Clone the repository and install the dependencies using `npm install`. Run the application locally using `npm start`.

## Contributions
Feel free to fork this repository and make contributions. Pull requests are welcome!

## License
This project is licensed under the MIT License. See `LICENSE` for more information.

## Contact
If you have any questions or suggestions, feel free to open an issue or pull request, or you can reach out to me directly.

Enjoy exploring the React-Matrix-Pathfinder!
