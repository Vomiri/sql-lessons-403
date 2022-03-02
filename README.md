# sql-lessons-403

Create database if not exists Sqlbd CHARACTER SET utf8 COLLATE utf8_general_ci; //создание бд с проверкой
USE Sqlbd; //"заходим" в нужную нам бд
CREATE TABLE IF NOT EXISTS test_table //создаем таблицу
(

id INT PRIMARY KEY AUTO_INCREMENT, //столбец id первичный ключ, авто_повышение значения

name VARCHAR(255) NOT NULL, //столбец имени не пустой

);
