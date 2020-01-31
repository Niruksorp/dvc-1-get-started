
# Preparation

## 1. clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-1-get-started.git
cd dvc-1-get-started
```

## 2. Create and activate virtual environment

```bash
virtualenv venv
source venv/bin/activate
```

#### Install python libraries (including dvc)

```bash
pip install -r requirements.txt
```

#### install extension toc for JupyterLab

##### install NodeJS

* Linux (Debian/Ubuntu)

```bash
apt-get install -y curl python3-software-properties
curl -sL https://deb.nodesource.com/setup_12.x | bash -
apt-get install -y nodejs
``` 

* MacOS

```
https://treehouse.github.io/installation-guides/mac/node-mac.html
```

#### install toc

```bash
jupyter labextension install @jupyterlab/toc
```

    
### checkout new branch in demo repository (to not wipe content of master branch)

```bash
git checkout -b dvc-tutorial
``` 

# Step 1. Initialize & Setup DVC

In general https://dvc.org/doc/get-started/initialize 
1) project repository should have initiated .git (git init) 
2) than: dvc init - initiate DVC  

For this case: 
1) git is already initiated 

# Continue DVC tutorial

## Run notebook tutorial.ipynb

```bash
jupyter-lab tutorial.ipynb
```
    
