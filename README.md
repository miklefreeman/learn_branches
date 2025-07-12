...или создайте новый репозиторий в командной строке
echo "# learn_branches" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:miklefreeman/learn_branches.git
git push -u origin main
…или отправить существующий репозиторий из командной сторки
git remote add origin git@github.com:miklefreeman/learn_branches.git
git branch -M main
git push -u origin main
