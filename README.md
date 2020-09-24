# PWS-15_e1_travis-ci

[![Travis][build-badge]][build]
[build-badge]: https://img.shields.io/travis/LovingFox/PWS-15_e1_travis-ci/master.png?style=flat-square
[build]: https://travis-ci.org/LovingFox/PWS-15_e1_travis-ci

## Проект "Непрерывная интеграция с travis-ci"

Один файл с игрой "Висилица" и 5 тестов со 100% охватом кода


## Установка и запуск

  - скачать проект и перейти в директорию проекта
```
$ git clone https://github.com/LovingFox/PWS-15_e1_travis-ci
$ cd PWS-15_e1_travis-ci
```

  - запустить игру
```
$ pytest game.py
```

## Запуск тестов вручную

  - создать виртуальное окружение
```
$ python -m venv env
```

  - применить виртуальное окружение
```
### Если у вас Linux:
$ source env/bin/activate
### Если у вас Windows:
$ env\Scripts\activate.bat
```

 - установить зависимости
```
$ pip install -r requirements.txt
```

  - запустить тесты
```
$ pytest
$ pytest --cov
```
