# Codenames

This repository is an experiment to try to replicate the board game Codenames. The idea is create an AI able to play the game as leader and team member.

## Codenames: the board game

Codenames is a party game. The players divides in two teams. Each team have a leader.

The game starts with 25 words in a grid.

The goal of the each team is to guess their words in the grid. The leader says a word and a number, witch indicates how many words in the grid are related to it. The other team members have to select the words and try to guess with the correct ones.

## Conda

To create a conda environment, you have to use the command:

```sh
conda env create -f environment.yml
```

To activate the environment, use the following command:

```sh
conda activate telecom
```

Finally, to add kernel to Jupyter, you have to use `ipykernel` as follow:

```sh
python -m ipykernel install --user --name condenames --display-name "Python (condenames)"
```
