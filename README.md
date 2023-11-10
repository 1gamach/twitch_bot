# ravshann bot

%ping - проверка работоспособности бота, время работы бота

## Управление командами

* !addc <!команда> <сообщение>

Добавляет новую команду 

>Примечание: при добавлении команды не использовать двоеточие ( : ), вместо него можно использовать знак дефиса ( - ), в противном случае команда будет добавлена некорректно, если команда создалась некорректно можно зайти в файл commands.txt и удалить некорректную команду

* !editc <!команда> <новое сообщение>

Редактируют команду

* !delc <!команда>

Удаляет команду

## Управление интервалами

* !addinterval <количество отправок> <интервал в секундах> <сообщение> <индекс>

Добавляет интервал (отправка сообщения с определённым интервалом времени)

>Примечание: при добавлении интервала не использовать запятые ( , ) остальные символы можно, в противном случае интервал будет добавлен некорректно, если интервал создался криво можно зайти в файл intervals.txt и удалить некорректный интервал

* !startinterval <индекс>

Включает интервал по индексу

* !delinterval <индекс>

Удаляет интервал по индексу

* !intervalsoff

Отключает все активные интервалы

* !showintervals

Показывает список интервалов, их индексы и статусы (включен/отключен)

## Вспомогательная информация

* !addquote <текст>

Добавление новой цитаты

* !deletequote <индекс>

Удаляет цитату по индексу

---

У бота стоит ограничение спама в 20 сообщений, например, если отправить команду !тг 100, отправится ссылка на тг 20 раз, и так с любой командой из файла commands.txt

При возникновении ошибок с командами или интервалами, в файлах commands.txt и intervals.txt уже есть некоторые команды, можно посмотреть на них и попробовать найти ошибку
