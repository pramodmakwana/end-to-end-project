# This is my end to end project

# First initialize the git

git init



git add{file name.txt}

# to add folder in git
git add.

git commit -m "This is my first commit"

# for faching any changes in git hub enviorment below command
git pull



echo [$(date)]: "START"

echo [$[date]]: "creating env with python 3.8 version"

conda create --prefix ./env pyhton==3.8 -y

echo[$(date)]: "activating the enviornment"

source activate ./env

echo [$(date)]: "installing the dev requirements"

pip install -r requirements.txt

echo[$(date)]: "END"

 
