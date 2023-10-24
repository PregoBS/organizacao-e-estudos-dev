# Python Utils and Helpers

[Conda Doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

To create an environment:
```
conda create --name myenv
conda activate myenv
conda deactivate
```
To create an environment with a specific version of Python:
```
conda create -n myenv python=3.9
```
To create an environment with a specific package:
```
conda create -n myenv scipy
```