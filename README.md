Приложение третьего типа для Битрикс24 и WebHooks - упрощенный вариант rest-событий и rest-команд, без написания приложения.
Для выбора закомментировать лишнее (конфиг и require 'include/app.php'; или require 'include/hook.php'; соответственно)
Скрипт лежит на своем хостинге, по cron подключается к Битрикс24, проверяет не собирается ли кто-то из пользователей в отпуск через 3, 2 и 1 неделю, отправляет в Б24 уведомление об этом событии руководителю отправляющегося в отпуск сотрудника. Опционально можно оповещать сразу из скрипта по e-mail