# yamdb_final
yamdb_final
[![Django-app workflow](https://github.com/SergKuzora/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)](https://github.com/SergKuzora/yamdb_final/actions/workflows/yamdb_workflow.yml)

Проект создан Кузора Сергеем в процессе обучения в Яндекс.Практикуме на профессию python developer

Проект доступен по адресу: sergey-kuzora.ru

### Как запустить проект автоматически:

Для деплоя проекта на сервер достаточно сделать git push в репозиторий SergKuzora/yamdb_final

### Как запустить проект самостоятельно:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/oleg-rubtsov/api_yamdb.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```