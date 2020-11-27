# Инициализируем репу в текущей директории
git init <br/>
Добавляем .gitignore <br/>
git add . <br/>
git commit -m 'init'

# Подключаем удалённый репозиторинй и пушим в него данные
git remote 

### если git remote ни чего не вернул, то:
git remote add origin <htts or ssh repo> <br/>
git push -u origin master

### если git remote что вернул, то уже есть удалённая репа и нужно:
git remote set-url origin <htts or ssh repo> <br/>
git push -u origin master
