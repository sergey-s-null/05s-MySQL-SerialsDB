# Задача

1. Необходимо выбрать предметную область для создания базы данных. Была выбрана **база данных сериалов**.
2. Необходимо описать таблицы и их назначение. Выполнить проектирование логической структуры базы данных. Описать схему базы данных. Все реальные таблицы должны иметь 3 нормальную форму или выше. База данных должна иметь минимум 5 таблиц.
3. Необходимо разработать два клиентских приложения для доступа к базе данных. Данные приложения должны быть написаны на двух разных языках программирования и иметь разный интерфейс (например, классическое оконное приложение и web-приложение). Выбор языков программирования произволен.
4. Необходимо организовать различные роли пользователей и права доступа к данным. Далее, необходимо реализовать возможность создания архивных копий и восстановления данных из клиентского приложения.
5. При разработке базы данных следует организовать логику обработки данных не на стороне клиента, а, например, на стороне сервера, базы данных, клиентские приложения служат только для представления данных и тривиальной обработки данных.
6. База данных должна иметь представления, триггеры и хранимые процедуры, причем все эти объекты должны быть осмысленны, а их использование оправдано.

# База данных
## Сущности

![](_readme_files/things_conn.png)

## Структура

![](_readme_files/structure.png)

# [1-е приложение](https://github.com/Laiser399/05s-Java-SerialsDatabaseApp)

## Авторизация:

![](_readme_files/1stApp/auth.png)

![](_readme_files/1stApp/main.png)

## Изменение:

![](_readme_files/1stApp/update1.png)

![](_readme_files/1stApp/update2.png)

# [2-е приложение](https://github.com/Laiser399/05s-WEB-SerialsDBWebPage)

![](_readme_files/2ndApp/1.png)

![](_readme_files/2ndApp/2.png)