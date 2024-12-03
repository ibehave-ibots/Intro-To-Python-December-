## Exercise 1

1. Open mini prompt/anaconda prompt terminal
2. Ensure you see (base) in the terminal

## Exercise 2

1. Create a conda environment called `env_1` with python version 3.10

```shell
conda create -n env_1 python=3.10
```

2. Activate `env_1` 

```shell
conda activate env_1
```

3. Ensure you see (env_1) in the terminal

4. Install `numpy` inside `env_1`

```shell
pip install numpy
```

5. Deactivate `env_1` environment

```shell
conda deactivate
```

6. (Optional) On VS Code, check that you can select `env_1` as kernel

### Exercise 3

1. Create a conda environment called `env_2` with python version 3.12
2. Install `pandas` inside `env_2`

### Exercise 4

1. Create a conda environment called `suite2p` with python version 3.9
2. Install suite2p package with GUI inside the `suite2p` environment.

```shell
pip install suite2p[gui]
```
3. Once the installation is complete, open suite2p GUI by typing the below command in the suite2p environment

```shell
suite2p
```


