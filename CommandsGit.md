# Команды Git

Регистрация в Git
```sh
git config --global user.name "Имя"
git config ---global user.email "Эл. почта"
```

Создание репозитория
```sh
git init
```

Информация об изменениях в репозитории и текущей ветке
```sh
git status
```

Добавление файла для индексации
```sh
git add folder_name
```
Запись внесенных изменений с комментарием
```sh
git commit -m "Message"
```

Просмотр истории изменений с указнием комментариев
```sh
git log
git log --oneline
```
Переключение между комитами в репозитроии
```sh
git checkout numbercommit
```
Возврат к последней сохраненной версии
```sh
git checkout master
```

Просмотр отличий между двумя сохраненными версиями
```sh
git diff numbercommit1 numbercommit2
```