# **Probability and Statistics using Python**

This repository contains code and resources for learning and applying Probability and Statistics using Python in Machine Learning and other related fields.

## Getting Started

To get started with this repository, follow the steps below to set up your environment and install the necessary packages.

### Setting Up the Environment

Ensure you have `conda` installed on your system. If not, you can download and install it from the [official conda installation guide](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

1. **Create a virtual environment using conda:**
    ```bash
    conda create --prefix ./stats-env
    ```

2. **Activate the newly created virtual environment:**
    ```bash
    conda activate ./stats-env
    ```

3. **Change the environment prompt to show only the environment name:**
    ```bash
    conda config --set env_prompt '({name}) '
    ```

4. **Deactivate and reactivate the environment to apply the prompt change:**
    ```bash
    conda deactivate
    conda activate ./stats-env
    ```

### Installing Essential Packages

With the virtual environment activated, install the necessary packages for this project.

1. **Install Jupyter Lab, pandas, and matplotlib:**
    ```bash
    conda install jupyterlab pandas matplotlib
    ```

2. **(Optional) Install pandas again for clarity (redundant):**
    ```bash
    conda install pandas
    ```

3. **Install bokeh for interactive visualizations:**
    ```bash
    conda install bokeh
    ```

4. **(Optional) Install matplotlib again for clarity (redundant):**
    ```bash
    conda install matplotlib
    ```

### Starting Jupyter Lab

Once all the packages are installed, you can start Jupyter Lab to begin working interactively with your notebooks.

```bash
jupyter lab
