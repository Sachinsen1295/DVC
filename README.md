## Create conda env

````
conda create -p venv python=3.8 -y
````
````
touch README.md
````
````
pip install -r requirements.txt
````

## Activate DVC
````
dvc init
````

create dvc,yaml file and create connents

# after that run 

````
dvc repro
````

````
dvc dag
````

for further info https://github.com/sunnysavita10/dvc