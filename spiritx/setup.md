#### Installation

##### create environment
to make sure that all dependencies are running as intended, run
`conda env create -f environment.yml`
if you have a lot of virtual environment installed you may want to edit the first line in `environment.yml` to
` name: /path/to/your/homedatafolder/lagranto`
and adjust the last line `prefix` with the same expression in order to avoid memory errors. 

to use the environment run:
`conda activate lagranto`
or, if you specified name and repfix use that expression. to make the environment usable for jupyter install a kernel dependency as
`python -m ipykernel install --user --name my-kernel --display-name="00lagranto"`

