### инициализация
> git init\
> git status



### переименовали ветку
> git branch -m master main\
> git branch -M main



### коммитим
> git add .\
> git commit -m "initial project version"



### cвязываем наш локальный репозиторий с репозиторием на на GitHub
> git remote add origin https://github.com/ustyugovki/depo.git



### отправка изменений на сервер
> git push -u origin main



### запрос изменений с сервера
> git pull origin main\
> git pull origin module2-task1



### отправка изменений на сервер
> git branch module1-task1\
> git checkout module1-task1\
> git add .\
> git commit -m "Запустил проект"\
> git push --set-upstream origin module1-task1\



### мердж ветки в мастер
> git checkout main\
> git merge module1-task1\
> git push origin main



### отменить выполнение команды git add:
> git restore --staged .



### посмотреть коммиты:
> git log\
> git log --oneline\
> git log --oneline --graph\
> git log --oneline --graph --all



### посмотреть выбранный коммит:
> git show hash_commit



### переделать commit message и внести туда новый комментарий:
> git commit --amend -m 'Новый комментарий'



### удаление локальной ветки
> git branch -d mybranch

