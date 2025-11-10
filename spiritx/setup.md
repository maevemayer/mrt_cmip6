#### Installation

##### create environment
- first install miniconda if not existing <br>
`wget https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Linux-x86_64.sh` <br>
`chmod +x Miniforge3-Linux-x86_64.sh` <br>
`./Miniforge3-Linux-x86_64.sh` <br>
- to make sure that all dependencies are running as intended, run <br>
`conda env create -f environment.yml` <br>
- if you have a lot of virtual environment installed you may want to edit the first line in `environment.yml` to <br>
` name: /path/to/your/homedatafolder/lagranto` <br>
- and adjust the last line `prefix` with the same expression in order to avoid memory errors. <br>
- to use the environment run:<br>
`conda activate lagranto` <br>
- or, if you specified name and repfix use that expression. to make the environment usable for jupyter install a kernel dependency as<br>
`python -m ipykernel install --user --name my-kernel --display-name="00lagranto"`

