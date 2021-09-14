create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

created a req file

install the req
'''bash
pip install -r requirements.txt
'''

git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"

git add . && git commit -m "update README.md"

git remote add origin https://github.com/DebanjanCoder/simple_app.git

git branch -M main

git push -u origin main