echo > README.md
git add README.md "Мой первый проект"
git commit -m "Добавил README.md"

git status > status.txt
git add status.txt
git commit -m "Добавил status.txt"

git log --oneline --all > log.txt
git add log.txt
git commit -m "Добавил log.txt"

git push
