# Код для скринкаста по Node.JS

Страница скринкаста: [http://learn.javascript.ru/nodejs-screencast](http://learn.javascript.ru/nodejs-screencast).

Код есть для всех выпусков, где он важен.

- Модули для Node.JS `[modules-1-intro]`
  1. Файл с классом User
  2. Простой require (не работает)
  3. Пример require + exports 
  4. Экспортируем User с помощью global
  5. Вынос фраз в модуль ru.json
  6. Вынос user в директорию

- Приёмы работы с модулями `[modules-2-module]`
  1. Сервер с запуском в режиме экспорта или приложения 
  2. Экспорт функции через module.exports
  3. Использование "базы данных" db в server и user
  4. Поиск db без пути, модуль в node_modules
  5. Добавление логгера

- Модуль util и наследование `[top-1-util]`
  1. Пример использования format
  2. Пример использования inspect
  3. Пример использования inherit

- Модуль console `[top-2-console]`
  1. Вызовы методов консоли

- Наследование от ошибок Error `[top-3-inherit-error]`
  1. Пример кода без обработки ошибок
  2. Добавлены классы ошибок и их обработка

- События, EventEmitter и утечки памяти `[top-4-eventemitter]`
  1. Демо EventEmitter
  2. Демо обработки ошибок
  3. Исходный объект Request, без утечек памяти
  4. Утечка памяти с предупреждением от EventEmitter
  5. Исправленная утечка 

- Node.JS как веб-сервер `[server-1-intro]`
  1. "Привет, мир"
  2. "Привет, мир" со счётчиком
  3. Вывод событий в консоль

- Эхо-сервер на Node.JS `[server-2-echo]`
  1. Echo-сервер

- Документация к модулю http `[dev-3-module]`
  1. Логирование при помощи debug
  2. Логирование обёрткой над winston

- Введение в асинхронную разработку `[event-loop-1-async]`
  1. Синхронный сервер для index.html
  2. Асинхронный сервер для index.html
  3. Синхронный сервер с try..catch для index.html

- Таймер, process.nextTick, ref/unref `[event-loop-3-timers]`
  1. Простой сервер на 2.5 секунды
  2. Тот же сервер с выводом памяти по setInterval
  3. Сервер после вызова timer.unref()
  4. Демо разницы между nextTick и setImmediate

- Асинхронный try..catch, домены


- Работа с файлами, модуль fs `[fs-1-fs]`
  1. Чтение readFile в буфер
  2. Чтение несуществующего файла, ENOENT
  3. Пример stats
  4. Пример writeFile - rename - unlink

- Работа с путями от пользователя `[fs-2-path]`
  1. Сервер отдачи файлов из директории public

- Потоки в Node.JS, fs.ReadStream `[streams-1-writable]`
  1. Чтение маленького файла через fs.ReadStream
  2. Чтение большого файла
  3. Обработка ошибок

- Writable-поток ответа res, метод pipe `[streams-2-net]`
  1. Отдача большого файла без потоков
  2. Отдача большого файла через read - drain - write
  3. Замена на встроенный метод pipe
  4. Отдача файла через pipe с обработкой ошибок и обрыва связи

- Чат через long-polling `[long-poll-chat]`
  1. Чат: клиент и сервер
