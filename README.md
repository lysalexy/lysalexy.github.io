## Запуск

### Требования:

- Make
  (Под Windows можно установить [cygwin](https://www.cygwin.com/install.html) и указать путь до cygwin64\bin\sh.exe)

- [NodeJS](https://nodejs.org/en/download)
- resume cli

```
npm install -g resume-cli
```

### Цели Makefile

| Цель     | Назначение                                   |
|----------|----------------------------------------------|
| css      | Копирование стилей                           |
| en       | Генерация .html & .pdf resume/en/resume.json |
| ru       | Генерация .html & .pdf resume/ru/resume.json |
| en-serve | Хостинг .html en                             |
| ru-serve | Хостинг .html ru                             |
