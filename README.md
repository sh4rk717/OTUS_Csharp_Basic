# OTUS_Csharp_Basic
Telegram bot for movie searching


1. Телеграм-бот по поиску фильмов по фильтрам.
Возможность добавлять фильмы в избранное

2. - Пользователь
	- Админ

3. Пользователь
- поиск по названию, части названия
- поиск по году релиза (<, >, = )
- поиск по жанру
- поиск по актеру
- добавить фильм в свой список
- удалить фильм из списка
- просмотреть свой список

	Админ
- добавить фильм в список любого пользователя
- удалить фильм из списка любого пользователя
- ...

4. Базовые функции (4 шт.)
- f1 - поиск фильма по названию, части названия
- f2 - вывод подробной информации о фильме
- f3 - добавить фильм в свой список
- f4 - просмотреть свой список

5. **Пользователь**: "/start"  
**Бот**: "Найти фильм/Избранное/"  
**Пользователь**: "Найти фильм"  
**Бот**: "Введите название или его часть"  
**Пользователь**: "Bond"  
**Бот**: "Найдено ххх фильмов. Вот 10 из них" (f1)  
	1) ...  
	2) ...  
	   ...  
	10) ...  
 
	**Бот**: "Вывести подробную информацию о фильме/Добавить фильм в избранное"  
	**Пользователь**: "Вывести подробную информацию о фильме"  
	**Бот**: "Введите номер фильма"  
	**Пользователь**: "1"  
	**Бот**: "...инфа о фильме..." (f2)  
	**Бот**: "Добавить этот фильм в избранное/Начать новый поиск"  
	**Пользователь**: "Добавить фильм в избранное"  
	**Бот**: "Добавлено в избранное" (f3)  
	**Бот**: "Найти фильм/Избранное/"  
	**Пользователь**: "Избранное"  
	**Бот**: 1. ...			(f4)   
		  2. ...   
		...	   
	**Бот**: "Найти фильм/Избранное/"  
