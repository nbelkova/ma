# Miniapps test bot

(Леша, тут кусочки по msisdn confirmation, secret input, send file повторяются)

Бот на русском языке. Данный бот представляет собой пример использования следующих плагинов: 

- msisdn confirmation
- secret input
- send file
- Smartcash
- Оплата в типей

Msisdn-confirmation

Цель бота получить от пользователя подтвержденный номер телефона.
Бот предлагает сделать верификацию с помощью:
1) c2s
2) SMS
3) USSD
4) скинуть предыдущие авторизации (верификации).

Secret-input-sample
Цель бота предоставить способ ввода пароля в чате Telegram без сохранения его в истории переписки.
На первой странице бот предупреждает, что на следующей странице нужно будет ввести пароль. 
На следующей странице появляется инпут для пароля. Кнопки: Готово, Отмена.
В случае, если пароль был введен, бот подтверждает успешное введение пароля.

Send file
Бот представляет собой пример использования sender plugin.
Бот предлагает послать:
- картинку в BASE64
- картинку из статического ресурса
- координаты
- PDF-файл 
