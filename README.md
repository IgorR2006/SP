<div align="center"> <h1> АВТОМАТИЗАЦИЯ ТЕСТИРОВАНИЯ. ПРОЕКТ SHOPILAND </h1></div>

<h4> Объект тестирования: https://shopiland.ru/ </h4>

<h4> Для тестирование использовались: </h4>
<p> 1. PyCharm IDE (+ необходимые библиотеки указаныне в requirements.txt) - для написание автотестов </p>
<p> 2. DevTools - для построения локаторов <p>

 - В папке pages содержатся исходные данные, локаторы, функции
 - В папке tests содержатся тесты

Для тестирования необходимо установить пакеты указанные в файле: requirements.txt 
Запуск автоматической установки pip3 install -r requirements.txt

Запуск тестов (путь к драйверу необходимо изменить на актуальный):
python -m pytest -v --driver Chrome --driver-path C:\Projects\SeleniumDriver\Chrome\chromedriver.exe tests/test_search_page.py

<div align="center"> <h4> Тестовая документация проекта  <a href="https://docs.google.com/spreadsheets/d/1QQkWSXcze6gbAL9qi6l7aPjc74ZTPFZW/edit?usp=sharing&ouid=103842292872009011194&rtpof=true&sd=true"> Содержит тест - кейсы, чек - листы и баг-репорты </a> </h4></div>
