OS Ubuntu 22.04

Создать базу MySql -chatdb.

Компиляция серверной части
g++ -std=c++2a -o server $(mysql_config --cflags) *.cpp $(mysql_config --libs)

компиляция клиентской части
g++ -o client *.cpp


