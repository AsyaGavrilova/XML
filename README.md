# Домашнее задание XML
 1. Создать внешний репозиторий c названием XML.
> Repositories - New - Create repository

 2. Клонировать репозиторий XML на локальный компьютер.
> git clone git@github.com:AsyaGavrilova/XML.git

 3. Внутри локального XML создать файл “new.xml”.
> touch new.xml

 4. Добавить файл под гит.
> git add new.xml

 5. Закоммитить файл.
> git commit -m 'Added new file xml'

 6. Отправить файл на внешний GitHub репозиторий.
> git push

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
> cat >> new.xml <br/>
Enter
<?xml version="1.0" encoding="utf-8"?>
	<composition>
		<firstName>Анастасия</firstName>
		<lastName>Гаврилова</lastName>
		<age>35</age>
		<pets>0</pets>
		<desiredSalary>50000</desiredSalary>
	</composition>
> Enter
> Ctrl+C

 8. Отправить изменения на внешний репозиторий.
> git add new.xml <br/>
> git commit -m 'Update new.xml' <br/>
> git push

 9. Создать файл preferences.xml
> touch preferences.xml

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
> cat >> preferences.xml <br/>
> Enter
<?xml version="1.0" encoding="utf-8"?>
	<composition>
		<favoriteMovie>Из машины</favoriteMovie>
		<favouriteSeries>Гримм</favouriteSeries>
		<favoriteFood>Шоколад</favoriteFood>
		<favoriteTimeOfYear>Лето</favoriteTimeOfYear>
		<countryIWantToVisit>Италия</countryIWantToVisit>
	</composition>
> Enter
> Ctrl+C

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
> cat >> skills.xml <br/>
> Enter
<?xml version="1.0" encoding="utf-8"?>
	<skills>
		<skill>
			<name>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC</name>
		</skill>
		<skill>
			<name>Что такое клиент-серверная архитектура</name>
		</skill>
		<skill>
			<name>HTTP Методы запросов на сервер</name>
		</skill>
		<skill>
			<name>Коды ответов HTTP сервера</name>
		</skill>
		<skill>
			<name>Структуры HTTP запросов и ответов</name>
		</skill>
		<skill>
			<name>Что такое JSON, XML. Их структура</name>
		</skill>
		<skill>
			<name>Тестирование API через Postman (JS, автотесты API)</name>
		</skill>
		<skill>
			<name>Снятие и чтение логов c внешнего сервера</name>
		</skill>
		<skill>
			<name>Снифинг http web трафика через Charles и Fiddler</name>
		</skill>
		<skill>
			<name>Dev Tools веб браузеров (Google Chrome, FireFox)</name>
		</skill>
		<skill>
			<name>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</name>
		</skill>
		<skill>
			<name>Мобильное тестирование</name>
		</skill>
		<skill>
			<name>Особенность iOS, Android, гайдлайны</name>
		</skill>
		<skill>
			<name>Сборка iOS приложений на XCode</name>
		</skill>
		<skill>
			<name>Сборка Android приложений на Android Studio</name>
		</skill>
		<skill>
			<name>ADB (управление андройд девайсами)</name>
		</skill>
		<skill>
			<name>Настройка прокси и vpn на iOS и Android</name>
		</skill>
		<skill>
			<name>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</name>
		</skill>
		<skill>
			<name>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</name>
		</skill>
		<skill>
			<name>Основы bash скриптинг, автоматизация рутинных задач на сервере</name>
		</skill>
		<skill>
			<name>Доступ к удалённым серверам</name>
		</skill>
		<skill>
			<name>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</name>
		</skill>
		<skill>
			<name>База данных Postgres (установка, настройка и использование)</name>
		</skill>
		<skill>
			<name>Нереляционная база данных Redis (установка, настройка и использование)</name>
		</skill>
		<skill>
			<name>Нагрузочное тестирование в Jmeter</name>
		</skill>
		<skill>
			<name>Методология разработки Scrum</name>
		</skill>
		<skill>
			<name>Python. (Изучение основ. Создание клиент серверного приложения)</name>
		</skill>
	</skills>
> Enter
> Ctrl+C

 12. Сделать коммит в одну строку.
> git add <br/>
> git commit -m 'Created 2 files xml'

 13. Отправить сразу 2 файла на внешний репозиторий.
> git push

 14. На веб интерфейсе создать файл bug_report.xml.
> Add file <br/>
> Create new file <br/>
> bug_report.xml

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
> Commit new file

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
> Открыть файл bug_report.xml <br/>
> Нажать "Edit this file" <br/>
> Добавить баг-репорт

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
> Добавить сообщение в коммит <br/>
> Нажать "Commit changes"

 18. Синхронизировать внешний и локальный репозиторий XML
 > git pull
