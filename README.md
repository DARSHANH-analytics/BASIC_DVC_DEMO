### Commands used in env setup
conda create -n env_name python=3.7 -y

conda activate env_name 
    or 
source activate env_name

### other commands
touch fileName.extension --> touch to create a new file

### Commands used in dvc
pip install dvc --> to install dvc package

dvc init ---> this is used to initialize/start dvc to track files, on execution of above command a .dvc folder,.dvcignore file gets created

touch dvc.yaml --> to create a dvc.yaml file, dvc.yaml file contains stages involved, files to run in particular stage, output files involved in the stage

dvc repro --> this command will check for availability of dvc.yaml file i.e. configurations file to understand the order of stages and files to start execution in the particular stage