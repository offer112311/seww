# seww Халюкину Пр-я Практика


TODO list:
- [x] Сделать функционал запоминания пароля и логина 
- [x] Сделать логгирования событий в mysql (вход/выход)
- [x] При авторизации пользователя, титулу окна формы Dashboard нужно присвоить текст "Панель управления " + должность пользователя(Клиент, менеджер, и.тд)
- [x] Для таблицы orders добавить новое enum-поле status, которое будет определять состояние заказа. (Обрабатывается/Обработан)
- [x] Для таблицы users добавить новое поле money, которое будет определять баланс пользователя. Так же, в эту таблицу нужно добавить логическое (bool) поле is_online, которое будет определять, авторизован ли данный пользователь сейчас в системе. Когда пользователь авторизовывался, полю is_online нужно присвоить true. Если же он вышел, то false.
