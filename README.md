
This repository contains four Jupyter Notebooks showing interactive examples of Earth Observation tasks using openEO Platform.

## Instructions

The easiest way to run the notebooks is by clicking the Binder button at the top. This will create an independent Python environment with all the required libraries, where you will be able to experiment the notebooks.

Alternatively, you can run them locally (please note: the Anaconda Python enviornment has been tested on Linux Ubuntu 18.04, on Windows it might not work due to different library versions):
1. Install Anaconda to manage virtual environments. You can follow the instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
2. Clone the repository and get into the repo folder:
 ```
        git clone https://github.com/SARScripts/SInCohMap
        cd SInCohMap
```
3. Create a new conda environment with the following command:
```
        conda env create -f environment.yml
```
4. Once the process is complete, you can activate the environment:
```
        conda activate sincohmap
```
5. Now you can start the Jupyter Notebook Server and use the notebooks, just typing:
```
        jupyter notebook
```
6. This should open up a new window in your default web browser, where you can select the notebook you prefer.
