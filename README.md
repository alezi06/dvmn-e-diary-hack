# e-diary-hack

### Описание

С помощью данного скрипта можно иcправить влохие оценки, удалить все негативные замечания, добавить похвалу.

### Использование

Развернуть сайт с [электронным дневником](https://github.com/devmanorg/e-diary.git).

Положить файл скрипта в корень сайта, рядом с `manage.py`.

Запустить интерактивную оболочку:

`python manage.py shell`

Импортировать модуль и запустить функцию `main`:

```sh

>>> import scripts

>>> scripts.main()
```

Так же можно импортировать и запускать функции отдельно:

```python

get_schoolkid(name) # получить ученика по имени

fix_marks(schoolkid) # исправить оценки

remove_chastisements(schoolkid) # удалить замечания

create_commendation(schoolkid, subject) # добавить похвалу
```

### Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).