https://github.com/NXGHTMXRE007/web1

# Лабораторная работа №1: Создание виртуального окружения. Контроллеры и маршруты

**Студент:** Евдокимов Иван Александрович
**Группа:** ПИЖ-б-о-25-2(1)

## Цель работы
Настроить виртуальное пространство. Разработать
контроллер приложения и организовать маршруты



## Выполнение практического  задания
Создание и активация виртуального окружения:
![0](screenshots/0.png)

![1](screenshots/1.png)
Установка Django:
![2](screenshots/2.png)
Проверка списка установленных пакетов:
![3](screenshots/3.png)
Создание проекта с именем MySite:
![4](screenshots/4.png)

![5](screenshots/5.png)
Запуск тестового сервера, чтобы проверить работу:
![6](screenshots/6.png)

![7](screenshots/7.png)
Открыл файл MySite/settings.py. Нашел список INSTALLED_APPS и добавил в конец строку 'news.apps.NewsConfig'
![8](screenshots/8.png)
Заменил содержимое news/views.py на следующий код:
![9](screenshots/9.png)
Создал urls.py внутри приложения news. Назвал файл urls.py. 
![10](screenshots/10.png)
Открыл главный файл маршрутов MySite/urls.py. Импортировал функцию include и добавьте маршрут для news/
![11](screenshots/11.png)
Запуск сервера:
![12](screenshots/12.png)
Проверка работоспособности:
![13](screenshots/13.png)

![14](screenshots/14.png)

![15](screenshots/15.png)

![16](screenshots/16.png)