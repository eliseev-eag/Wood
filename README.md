# Wood
Сайт по Командной разработке группы, состоящей из студентов Волкова, Елисеева и Ткаченко.

1. Устанавливаете PyCharm, pgAdmin 4.1, PostgresSQL_9.6.1_x64.
2. Загружаете проект на свой ПК.
3. Создаёте подключение к базе. Пользователь - postgres, пароль - 123.
4. Создаёте Database с названием wood.
5. Открываете проект в PyCharm.
6. В качестве конфигурации для исполнения нужно создать окружение и указать его.
7. Во вкладке Terminal в нижней панели выполняете следующие команды: "python -m pip install --upgrade pip", 
"pip install django", "pip install psycopg2", "python manage.py makemigrations", "python manage.py migrate".
8. Тут же вводится команда "python manage.py createsuperuser" и создается профиль администратора сайта.
9. Затем можно запустить сервер и перейти по адресу, который выводится в консоли.
10. Перейдя по адресу, дописываем в конец адреса "/admin" и вводим данные администратора.

Данных команд должно быть достаточно для работы.

