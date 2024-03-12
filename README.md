Домашнее задание к занятию "DDL/DML" - Медведев Владимир


### Задание 1

#Что нужно сделать:
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp.

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/CREATE.png)
![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/GRANTS.png)
![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/Диаграмма.png)
![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/Диаграмма1.png)
![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/Диаграмма2.png)


### Задание 2

#Что нужно сделать:

Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. 
![alt text](https://github.com/vladimir-medvedev/dz_DDL-DML/blob/main/Таблица.png)

