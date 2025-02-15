Инструкция к использованию автотестов

1. Установите Python на вашем компьютере если он еще не установлен:
https://www.python.org/downloads/

2. Установите Selenium WebDriver через pip:

bash pip install selenium

3. Скачайте драйвер ChromeDriver согласно версии вашего браузера Chrome:
https://chromedriver.chromium.org/downloads

4. Поместите файл chromedriver.exe в папку проекта.

5. Отредактируйте скрипт автотестов (test_script.py), указав правильный путь к chromedriver.exe:

python driver = webdriver.Chrome('/path/to/chromedriver')

6. Запустите скрипт автотестов из терминала:

bash python test_script.py
