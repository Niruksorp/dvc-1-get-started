
# Preparation

## 1. clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-1-get-started.git

cd dvc-1-get-started
```

## 2. Create and activate virtual enviromnent
Install virtualenv in advance: ```pip install virtualenv```

```
virtualenv venv

source venv/bin/activate
```

#### Install python libraries (including dvc)

```bash
pip install -r requirements.txt
```

    
### checkout new branch in demo repository (to not wipe content of master branch)

```bash
git checkout -b dvc-tutorial

``` 

# Step 1. Initialize & Setup DVC

In general https://dvc.org/doc/get-started/initialize 
1) project repository should have initated .git (git init) 
2) than: dvc init - initate DVC  

For this case: 
1) git is already initiated 


### initialize DVC 
```bash
dvc init
```
### commit dvc init

```bash
git commit -m "Initialize DVC"
``` 

    
### overview results of dvc init

```bash
ls -a .dvc
cat .dvc/.gitignore
```
    
 ### configuration 
    

# Continue DVC tutorial

## Run notebook tutorial.ipynb

```bash
jupyter lab tutorial.ipynb
```

or 

```bash
jupyter notebook tutorial.ipynb
```
    
