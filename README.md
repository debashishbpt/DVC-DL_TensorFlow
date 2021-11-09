# DVC - DL -TF- AIOPS

download data --> [source](https://drive.google.com/drive/folders/1tz4IOoJKdi999IRdqJY04VOifyllRzj1?usp=sharing)
## commands -

### Create a new env
'''bash
conda create --prefix ./env python=3.7 -y
'''

### activate new env
'''bash
source activate ./env
'''

### init DVC
'''bash
git init
dvc init
'''

### create empty files & directories-
```bash
touch README.md .gitignore setup.py dvc.yaml params.yaml
mkdir -p config src/utils
touch config/config.yaml
touch config/secrets.yaml
```

### install src
```bash
pip install -e .
```
