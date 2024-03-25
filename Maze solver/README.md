# Maze Solver

This repository contains a Python script `maze.py` that solves a maze provided through a text file. The script utilizes various search algorithms to find the shortest path from the start point 'A' to the goal point 'B' within the maze.

## Installation

To run the maze solver, ensure you have Python installed on your system. Additionally, you need to have the Python Imaging Library (PIL) installed to generate maze images. You can install PIL via pip:

```bash
pip install Pillow
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/hamzahalhalabi1/ML-projects.git
```

2. Navigate to the `Maze solver` directory:

```bash
cd ML-projects/Maze\ solver
```

3. Run the script with a maze file as an argument. For example:

```bash
python maze.py maze.txt
```

Replace `maze.txt` with the path to your maze file. The maze file should follow the format where 'A' represents the starting point, 'B' represents the goal, ' ' represents empty spaces, and any other character represents walls.

## Features

- Supports various maze configurations.
- Utilizes stack-based frontier and queue-based frontier for searching.
- Outputs the solution path and the number of states explored.
- Generates an image of the maze with the solution path highlighted.

## Example

An example maze file (`maze.txt`) is provided within this repository for testing the script.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License 
