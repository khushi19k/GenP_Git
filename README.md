# GenP_Git
git clone https://github.com/JiyaVe/GenP_task2.git
git clone https://github.com/khushi19k/GenP_Git.git
cd GenP_Git
cp -r ../GenP_task2/* .
git checkout -b Task
git add .
git commit -m "My Work"
git push origin Task
git checkout main
git merge Task
git push origin main

