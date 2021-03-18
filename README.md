# Codenames

This repository is an experiment to try to replicate the board game Codenames. The idea is create an AI able to play the game as leader and team member.

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
