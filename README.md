# вопросы
1) у меня почему-то все файлы (напр., manage.py, db.sqlite2, pyvenv.cfg и т.д.) подсвечиваются красным; 
когда я изучала модуль и делала все по видео, такого не было. В чем модет быть дело, если все работает?
2) имя - admin, пароль - password (это не вопрос, а просто чтобы было)
3) нужен ли здесь -> {{ flatpage.content }} отступ перед и после flatpage.content? Так было сделано на скринкастах в модуле. Это обязательно? Это что-то типа хорошей морской практики, так сказать?
4) мне кажется, что я не совсем то сделала, так как не использовала методы include и extends (хотя они были в модуле, значит, нужно было использовать?).
5) У меня были проблемы с расположением папок. Я делала все, как в скринкастах, но у меня так не работало, поэтому я содавала папки там, где они у меня работают. Т.е. сейчас все находится на своих местах, все работает, все хорошо. Надеюсь, у вас тоже будет работать. 


Для вашего удобства:
1) http://127.0.0.1:8000/fp1/ - контент повторяется 2 раза без изменения content (два раза прописано {{ flatpage.content }}) 
2) http://127.0.0.1:8000/fp2/ - доступна только админу 
3) http://127.0.0.1:8000/fp3/ - изменены шрифты и размеры текста (я тут попробовала разных штук, но не сильно много; у меня не было цели сделать красиво).
4) http://127.0.0.1:8000/main/ - предполагаемая главная страница с использованием bootstrap (выполняет пункт 6 задания: Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными). Надеюсь, я все правильно поняла. 
