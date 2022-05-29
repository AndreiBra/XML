# XML
 21. Создать внешний репозиторий c названием XML.    
```bash
На вэбе Repositories --> New --> Repos Name:XML --> Check "Add a README file" --> Press "Create repository"
```
 22. Клонировать репозиторий XML на локальный компьютер.
```bash
git clone <repository_linkHTTPS>
```
 23. Внутри локального XML создать файл “new.xml”.
```bash
touch new.xml
```
 24. Добавить файл под гит.
```bash
git add new.xml
```
 25. Закоммитить файл.
```bash
git commit -m "add new file"
```
 26. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```bash
cat > new.xml  --> ^C
or
vim new.xml
```
```bash
#for exapmle
<?xml version="1.0" encoding="utf-8"?>
<information_about_yourself>
	<full_name> Bragin Andrei Aleksandrovich</full_name>
	<age>47</age>
	<number_of_pets>1</number_of_pets>
	<future_desired_salary>1000</future_desired_salary>
</information_about_yourself>
```
 28. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add info in fale "   --> git push
```
 29. Создать файл preferences.xml
```bash
touch preferences.xml
```
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```bash
cat > preferences.xml  --> ^C
or
vim preferences.xml
```
```bash
#for example
<?xml version="1.0" encoding="utf-8"?>
<my_preferences>
		<favorite_movie>Forrest Gump</favorite_movie>
		<favorite_series>Breaking Bad</favorite_series>
		<favorite_food>fruits</favorite_food>
		<favorite_time_of_year>winter</favorite_time_of_year>
		<country_you_would_like_to_visit>Maldives</country_you_would_like_to_visit>
</my_preferences>
```
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```bash
cat > skills.xml  --> ^C
or
vim skills.xml
```
```bash
#for example
<?xml version="1.0" encoding="UTF-8"?>
<Skills_I_Learn>
	<Skill1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC"</Skill1>
	<Skill2>Что такое клиент-серверная архитектура.</Skill2>
	<Skill3>HTTP Методы запросов на сервер.</Skill3>
	<Skill4>Коды ответов HTTP сервера.</Skill4>
	<Skill5>Структуры HTTP запросов и ответов.</Skill5>
	<Skill6>Что такое JSON, XML. Их структура.</Skill6>
	<Skill7>Тестирование API через Postman (JS, автотесты API).</Skill7>
	<Skill8>Снятие и чтение логов c внешнего сервера.</Skill8>
	<Skill9>Снифинг http web трафика через Charles и Fiddler.</Skill9>
	<Skill10>Dev Tools веб браузеров (Google Chrome, FireFox).</Skill10>
	<Skill11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</Skill11>
	<Skill12>Мобильное тестирование.</Skill12>
	<Skill13>Особенность iOS, Android, гайдлайны.</Skill13>
	<Skill14>Сборка iOS приложений на XCode.</Skill14>
	<Skill15>Сборка Android приложений на Android Studio.</Skill15>
	<Skill16>ADB (управление андройд девайсами).</Skill16>
	<Skill17>Настройка прокси и vpn на iOS и Android.</Skill17>
	<Skill18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</Skill18>
	<Skill19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</Skill19>
	<Skill20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</Skill20>
	<Skill21>Доступ к удалённым серверам.</Skill21>
	<Skill22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</Skill22>
	<Skill23>База данных Postgres (установка, настройка и использование).</Skill23>
	<Skill24>Нереляционная база данных Redis (установка, настройка и использование).</Skill24>
	<Skill25>Нагрузочное тестирование в Jmeter.</Skill25>
	<Skill26>Методология разработки Scrum</Skill26>
	<Skill27>Python. (Изучение основ. Создание клиент серверного приложения)</Skill27>
</Skills_I_Learn>
```
 32. Сделать коммит в одну строку.
```bash
git add . && git commit -m "add skills"
```
 33. Отправить сразу 2 файла на внешний репозиторий.
```bash
git push
```
 34. На веб интерфейсе создать файл bug_report.xml.
```bash
Add file --> Create new file --> Name: bug_report.xml
```
```bash
#for example
<?xml version="1.0" encoding="utf-8"?>
<bug_report_structure>
    <summary>краткое описание</summary>
    <project>проект</project>
    <Environment>окружение</Environment>
    <ID>BUG_ID</ID>
    <component>компонент приложения</component>
    <version>номер версии</version>
    <severity>серьезность</severity>
    <priority>приоритет</priority>
    <steps_to_reproduce>шаги воспроизведения</steps_to_reproduce>
    <actual_result>фактический результат</actual_result>
    <expected_result>ожидаемый результат</expected_result>
    <additional_information>дополнения</additional_information>
</bug_report_structure>
```
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```bash
Choose bug_report.xml --> Edit this file
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```
 38. Синхронизировать внешний и локальный репозиторий XML
```bash
git pull
```
___


## Видео по вышеуказанному заданию можно посмотреть [здесь](https://youtu.be/DEAemHvkV3E)
___
