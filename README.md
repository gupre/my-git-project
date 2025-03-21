# My Git Project

git help # Открывает справку по командам Git

mkdir my-git-project # Создаем папку для проекта
cd my-git-project # Переходим в созданную папку
git init # Инициализируем новый локальный Git-репозиторий

git status # Проверяем состояние репозитория (какие файлы изменены, что еще не добавлено в индекс и т. д.)

echo "# My Git Project" > README.md # Создаем файл README.md с заголовком
git add README.md # Добавляем файл в индекс (staging area)
git commit -m "Добавлен README.md с описанием проекта" # Делаем первый коммит с комментарием
git log --oneline # Выводим историю коммитов в кратком формате

git branch feature # Создаем новую ветку с именем "feature"
git checkout feature # Переключаемся на ветку "feature"

echo "console.log('Hello, Git!');" > script.js # Создаем файл script.js с простым выводом в консоль
echo "body { font-family: Arial; }" > styles.css # Создаем файл styles.css с базовым стилем

git add script.js styles.css # Добавляем новые файлы в индекс
git commit -m "Добавлены script.js и styles.css" # Создаем коммит с новыми файлами

git add README.md # Добавляем измененный README.md в индекс
git commit -m "Обновлен README.md с описанием использованных команд" # Коммитим обновленный README.md

git remote add origin https://github.com/gupre/my-git-project.git # Добавляем удаленный репозиторий на GitHub
git remote -v # Проверяем список привязанных удаленных репозиториев

git branch -M main # Переименовываем текущую ветку в main (если требуется)
git push -u origin main # Отправляем основную ветку main в удаленный репозиторий

git checkout -b feature # Создание и переключение на новую ветку
git add . # Добавляем новые файлы в индекс
git commit -m "Добавлены новые файлы в ветке feature" # Коммитим обновленную ветку

git push -u origin feature # Отправляем ветку feature в удаленный репозиторий

git checkout main # Переключаемся обратно на основную ветку main
git pull origin main # Обновляем локальную ветку main, подтягивая изменения с удаленного репозитория
