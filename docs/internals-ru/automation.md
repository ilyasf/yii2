Автоматизация
=============

При работе над Yii, некоторые задачи, можно выполнять автоматически:

- Генерация карты классов в файл `classes.php`, который находится в корневой директории фреймворка.
  Запустите `./build/build classmap` для его генерации.

- Генерация аннотаций `@property` в файлах классов, описывающих свойства введённые геттерами и сеттерами.
  Запустите `./build/build php-doc/property` для их обновления.

- Исправление стиля кодирования и других мелких ошибок в коментариях phpdoc.
  Запустите `./build/build php-doc/fix` для их исправления.
  Проверьте изменения перед тем как их закомитить, так как могут быть нежелательные изменения, потому что команда не
  является совершенной. Вы можете использовать `git add -p` для обзора изменеий.
