# Create Conda Environment with Miniconda
I am creating a conda environment for DESeq2 data analysis with 
with R andf Bioconductor in my windows system using Windows
Subsystem Linux

## Code in WSL terminal
- Start the WSL in Windows
- Type the following to create a conda environment for R4.5 names as R4.SWS 
```{CMD}
conda create --name R4.SWS
```
- Activate the R4.SWS conda environment as follows
```{CMD}
conda activate R4.SWS
```
- Install R4.5 in the R4.SWS conda environment
```{CMD}
conda install conda-forge::r-base
```
`conda-forge` is the channel from anaconda.org. [conda-forge/r-base](https://anaconda.org/channels/conda-forge/packages/r-base/overview)
