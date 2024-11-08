# Сборка проекта с использованием webpack

Если приложение разложено по нескольким файлам,
собрать их в один файл, который можно будет
подтянуть в браузер можно при помощи webpack

## Самый простой способ настроить webpack

```sh
$ npm init --yes
$ npm install -DE webpack webpack-cli
```

Конфигурация? Нужна, но можно без нее.

```txt
src/
  index.js // отсюда начнется сборка
  ...
dist/
  main.js // сюда webpack сложит результат
```
```sh
$ npx webpack build --mode=production
```

