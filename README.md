Selfy CMS - Графическое web-ПО, облегчающий администрирование и разработку сайтов любой сложности

	#Системные функции
	hackDir() - считывает папку на наличие в ней папок с приложениями (в папках приложений ищет iframe.php или index.php)

	#Системные массивы
	$error - сборщик ошибок в системе
	$systemData - данные из БД
	$readmemory - расходные данные системы

	#Подключения к БД
	$systemData - общий массив вытащенный из textJSON
	$conn - PDO экземпляр
	$dbcnx - дескриптор MySQL {пример - mysql_fetch_row(mysql_query("SELECT text FROM  data", $dbcnx));}
	
	#Приложения по умолчанию (некомерческие):
	1. FTP клиент
	2. CSS3 - генератор
	3. CSS оптимизатор
	

0.03 version

	#кодировка сервера UTF-8
	#запрещаем нежелательный просмотр системных папок и файлов
	#автоматическое сжатие файлов на сервере
	#GZIP сжатие
	#Исполняемый файл для стартовой страницы - index.php
	#При установке платформы на сервер пользователь имеет пустой каталог с одним index.php, 
	относительно которого может хранить свои js, css, img, php файлы

	#Для создания динамического генерирования контента используется библиотека - jQuery v. 1.9.10
	#В качестве CSS сброса используется библиотека - reset.css (Mayer reset) и normalize.css
	#В качестве css-препроцессора используется библиотека natali
	#Существует предзагрузчик панели управления
	#http://ВАШ_САЙТ/admin/ - доступ в панель администратирования
	#Имеется вывод расхода оперативной памяти сервера данной платформой
	#Адаптивный вывод аварийных ситуаций в системе (если произошла ошибка, в меню будет показано)
	#Защита системных приложений от прямого вызова (не из панели управления)
	#Управляемые настройки файла конфигураций (БД)
	#Панель приложений для распределенных модальных приложений (страничные)
	#Панель задач - удобное управление задачами, выбор панели приложений, инструментов, выбор страниц редактирования

	
