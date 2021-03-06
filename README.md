# ml-base
Highly opinionated starter for machine learning projects. I will be starting from scratch (i.e empty repo).
Includes:
- ML-Framework: PyTorch (Tensorflow is great for production)
- Monitoring: Comet.ml
- Conda Envs
- VS Code (with configs and extensions)
- Linting and Code Formatters

Also includes markdown files for:
- Setting up Cloud Computing (Google Cloud, AWS, University of Edinburgh Informatics Clusters)
- Panda (All the things I search on stackoverflow everytime)

Also also includes jupyter notebooks for:
- Common Data Analysis things
- Mini-Project 1: .....
- Mini-Project 2: .....

Also also also includes scripts for:
- setting up dev environment on brand new computer
- scheduling jobs on cluster


## Conda Commands
update conda itself
```
conda update conda
```
create environment with latest python
```
conda create -n mlbase python
```
save conda environment (clean)
```
conda env export --from-history | grep -v "prefix" > environment.yml
```
## Git Commands

List curent remotes
```
git remote -v
```
Rename origin to upstream
```
git remote rename origin upstream
```
Add new origin
```
git remote add origin https://github.com/mnm-matin/Machine-Learning-Practical.git
git fetch origin
```

Disable Upstream Push
```
git remote set-url --push origin no_push
```
Pull from upstream
```
git pull upstream mlp2021-22/coursework2
Note: use --reabase for pulling for syncing changes
```
## VSCODE
keyboard shortcuts
```
Ctrl + Alt + Up/Down    Add Cursors
Shift + Alt + Up/Down   Copy Line Up/Down
Alt + Up/Down           Move Line(s) Up/Down
Ctrl + D                Add Cursor next to match
Ctrl + U                Cursor Undo
Ctrl + Shift + \        Go to Bracket
Ctrl + ]                Indent Line Forward
Ctrl + W                Close Tab
```
