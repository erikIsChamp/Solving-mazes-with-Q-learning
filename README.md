# Solving Mazes using Q-learning

This project is an extension from the Science Buddies project [here](https://www.sciencebuddies.org/science-fair-projects/project-ideas/ArtificialIntelligence_p008/artificial-intelligence/machine-learning-maze), implementing Q-learning agents to solve mazes.

## Using the Code

### Model Training
- `model_1.ipynb`, `model_2.ipynb`, and `model_3.ipynb` implement Q-learning agents with specified parameters and train on a chosen maze. Each notebook contains the training progress and results for the respective model.

### Maze Generation
- `maze_generator.ipynb` generates a random maze with a specified height and width. Note that the generated code isn't particularly elegant, but it works. Setting the height and width to even numbers will result in a +1 on your dimensions. The generated mazes are saved in the `mazes/` directory.

### Model Comparison
- `compare_models.ipynb` can be used to plot the training data from the models on top of each other for comparison. It uses the `plot_comparison` function to visualize the performance of `model_1`, `model_2`, and `model_3`.

### Training Data
- The training data for each model is saved in the `training_data/` directory as `.npy` files. These files can be loaded and used for further analysis or comparison.

## Directory Structure

- `compare_models.ipynb`: Notebook for comparing the performance of different models.
- `maze_generator.ipynb`: Notebook for generating random mazes.
- `mazes/`: Directory containing generated maze layouts.
- `model_1.ipynb`: Notebook for training and evaluating Model 1.
- `model_2.ipynb`: Notebook for training and evaluating Model 2.
- `model_3.ipynb`: Notebook for training and evaluating Model 3.
- `training_data/`: Directory containing training data for each model.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- tqdm