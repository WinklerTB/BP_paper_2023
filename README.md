# BP_paper_2023
This repository reproduces data and figures used in the publication "Energetics and Dynamics of a stable Bloch point" by Winkler et al. (2023), arxiv:2303:10091. url:  https://arxiv.org/abs/2303.10091. 
All scripts are provided by jupyter notebooks. Initial configurations are kept in this repo, but dynamics with large meshes (small discretizations) has to simulated with MicMag2. The code is open-source and can be found here: https://github.com/WinklerTB/MicMag2
For the evaluation of data MicMag2, the ubermag framework (https://ubermag.github.io), matplotlib and the plotly package are needed.

# 1. How To: Get all Data
In this repository only magnetization files smaller than 100 MB are already stored. There are two ways to get all necessary data:
## Way 1: Simulate Data
Install MicMag2 and run all the simulation scripts (this may take some time). The scripts names are all  "Run_*ipynb" notebook. 
## Way 2: Get Data from repository
You can download all necessary data from the Zenodo repository.DOI: 10.5281/zenodo.8264468

# 2. How To: Generate plots
Once you have all data present, you can rerun all evaluation scripts "Evaluate*.ipynb" to obtain all Figures from the manuscript

