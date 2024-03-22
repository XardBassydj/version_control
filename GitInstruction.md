# Подсказка по Git (Базовый набор команд)

* Инициализация нового репозитория:
```sh
git innit
```

* Клонирование существующего репозитория:
```sh
git clone <URL>
```

* Добавление изменений в индекс для подготовки к коммиту:
```sh
git add <файл>
```

* Создание коммита с описанием изменений:
```sh
git commit -m "Сообщение коммита"
```

* Показ текущего состояния рабочего каталога и индекса:
```sh
git status
```

* Просмотр истории коммитов:
```sh
git log
```

* Cокращение вывода коммитов до одной строки:
```sh
git log --oneline
```

* Показать список веток. 
```sh
git branch
```

* Переключение на другую ветку:
```sh
git checkout <ветка>
```

* Объединение изменений из указанной ветки в текущую:
```sh
git merge <ветка>
```

* Получение изменений с удаленного репозитория и объединение их с текущей веткой:
```sh
git pull
```

* Отправка коммитов на удаленный репозиторий:
```sh
git push
```

* Показать различия между рабочим каталогом и индексом:
```sh
git diff
```

* Сбросить изменения в указанных файлах:
```sh
git reset <файл>
```
* Удаление файлов из рабочего каталога и индекса:
```sh
git rm <файл>
``````

* Создание новой ветки:
```sh
git branch <имя_ветки>
``````

* Удаление ветки:
```sh
git branch -d <имя_ветки>
``````

* Команда  для вывода истории коммитов в виде графа:
```sh
git log --graph
``````