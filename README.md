# git-config

git config --list
git config --global user.name “имя”
git config --global user.email “почта”


git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main # Ветка по умолчанию
git config --global core.autocrlf true

git add . #  иниилизация репозитория
git init # добавить все файлы в track
git commit -m "сообщение" # сделать коммит
git status # показывает текущий статус
git diff - # показывает текущие изменения
git diff --color-words # покзывает более развернуто
git checkout . # вернуться к последнему коммиту

