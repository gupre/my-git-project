# My Git Project

mkdir my-git-project # создаем папку для проекта
cd my-git-project # заходим в папку
git init # инициализируем Git-репозиторий

git status

echo "# My Git Project" > README.md
git add README.md
git commit -m "Добавлен README.md с описанием проекта"
git log --oneline

git branch feature
git checkout feature
echo "console.log('Hello, Git!');" > script.js
echo "body { font-family: Arial; }" > styles.css
git add script.js styles.css
git commit -m "Добавлены script.js и styles.css"

git add README.md
git commit -m "Обновлен README.md с описанием использованных команд"
