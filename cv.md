# ***ANNA KOLESNICHENKO***
![Anna](.\DSCN0227.JPG "Anna")
******
### *CONTACTS*
1. tel: +375 29 704 37 24
2. e-mail: Anna-Vladi-2017@yandex.by
*****
#### About myself
********
I was born on May 24th. IM 42 years old. I have a husband and two sons.
When I was at school, I had a dream. Become a programmer.
And only now I have begun to fulfill my dream.
In 2021, I graduated from Python courses. But the front-end fascinated me more.
I have little experience in developing telegram bots and site administration.
Have experience with: VS Code, Web Storm, PyCharm.
In my work I used the following libraries: TelegramAPI, Aiogramm
```
@bot.message_handler(commands=['start'])
def send_welcome(message):
        print('def welcome')
        bot.send_photo(message.chat.id, "https://classpic.ru/blog/muravej-foto.html/chyornyj-sadovyj-muravej")
        markup = types.ReplyKeyboardMarkup(resize_keyboard=True, row_width=2)
        itembtn1 = types.KeyboardButton('about us')
        itembtn2 = types.KeyboardButton('application')
        markup.add(itembtn1, itembtn2)
        bot.send_message(message.chat.id, "Приветствуем ! "
                         + message.from_user.first_name
                         + ", я бот-ассистент, чем могу помочь?", reply_markup=markup)
```
*********
my level of English A2
*********
