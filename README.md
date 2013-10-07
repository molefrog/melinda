## Melinda 
Melinda — веб-приложение, позволяющее создавать свои собственные калейдоскопические 
визуализации.

### Зависимости
Melinda использует:
* Библиотеку [Graphemescope](https://github.com/Grapheme/graphemescope) для рисования калейдоскопов
* CoffeeScript, Express — на стороне сервера
* CouchDB для хранения данных

### Подготовка базы данных
Скрипт инициализирует базу данных (откатывает до начального состояния и удаляет все Скоупы!):
```
npm run-script scaffold
```

### Запуск
```
npm install
npm start
```

