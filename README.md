# Generative medical 3D volume

Based on a tutorial found in:

```{bash}
      https://github.com/Project-MONAI/GenerativeModels/blob/main/tutorials/generative/3d_ddpm/3d_ddpm_tutorial.ipynb
```

Create conda environment and import all required packages mentioned in the notebook.

```{bash}
      conda create -n monai python=3.11
      code .
```

### Observation

On a CPU system the GradScaler is not required. Batch size can be set to 16 on a 128GB machine.
