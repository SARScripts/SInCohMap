
# SInCohMap
Collection of code, notebooks and documentation for the SInCohMap project

## Instructions

You can run the notebooks locally (please note: the Anaconda Python enviornment has been tested on Linux Ubuntu 18.04, on Windows it might not work due to different library versions):
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

### Using an existing Jupyter instance

If there is already a Jupyter instance (i.e. the JupyterHub offered by Eurac Research), you can add the kernel from the newly created conda environment without running another one.
The necessary additional steps are:
```
$ conda activate sincohmap
(sincohmap)$ conda install ipykernel
(sincohmap)$ ipython kernel install --user --name=sincohmap
(sincohmap)$ conda deactivate
```
Source: [stackoverflow](https://stackoverflow.com/questions/53004311/how-to-add-conda-environment-to-jupyter-lab)

Please note: if your console does not recognize the `conda` command, you need to initialize it before running the previous commands, using:
`$ conda init bash`

Now the new kernel should be available in your Jupyter Lab. To use the new kernel:
1. Click on the kernel selector in the upper right corner of the page
2. Select the new kernel
3. Restart the kernel
![image](https://user-images.githubusercontent.com/31700619/150111234-6cf44258-5fc1-4746-837a-7884fb8939c3.png)
