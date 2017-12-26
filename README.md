# hello-worldsc

pip install twx.botapi

twx.botapi импорт TelegramBot, ReplyKeyboardMarkup
TelegramBot('<API ТОКЕН>')
update_bot_info().ждать()
user_id = инт(<someuserid>)
  результат = бот.send_message(функция user_id, 'тестовое сообщение тела').ждать()
печати(результат)
  обновления =бот.get_updates().ждать()
для обновления вобновления:
 печати(обновление)
  клавиатура =[
 ['7', '8', '9'],
 ['4', '5', '6'],
 ['1', '2', '3'],
 ['0']
]
reply_markup =ReplyKeyboardMarkup.создать(клавиатура)

бот.send_message(функция user_id, 'введите число', reply_markup=reply_markup).ждать()
