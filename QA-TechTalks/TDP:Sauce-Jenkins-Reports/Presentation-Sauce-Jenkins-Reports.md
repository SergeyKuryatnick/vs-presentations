footer: 
Ludmila Nesvitiy, AQA
© Valor Software, 2018
slidenumbers: true
autoscale: true
build-lists: true

![](valor_software.png)

---

# Sauce, Jenkins in TDP. BDD-Reports and analysing

## How to configure, debug, investigate? 

---
# Sauce, Jenkins in TDP. BDD-Reports and analysing
1. client/.env 
    1. SAUCE_LOGIN=
    2. SAUCE_KEY=
    3. SAUCE=true
    4. How to get this keys
    5. Where we use this keys (protractor-cucumber.conf, download PO)
2. Run tests on Sauce (change name, amount of threads, browser version and OS version)
3. How to analyze report with Saucelab
    1. Login to sauce and find your test runs 
    2. See video-recording command-logs
4. Jenkinsfile (Recruitment Platform stage SauceLabs): what credentials used, what commands
5. Jenkinsfile on CloudOps (for staging deployment, similar settings)
6. How to test changes to Jenkins file without deployment (Rerun functionality on Jenkins)
7. Full console log on Jenkins
8. Cucumber Report: commands for running
9. Generate-report.js file - how it works and when it uses
10. Analyze Cucumber Report: Feature file => Scenario => Show error = log from test failure => Show info = Console errors => Screenshot = screen from After hook
11. Developer question: how to run tests locally and didn’t block yourself? (use Docker and Selenoid for local testing, example of configuration and commands)

---

# [fit] Большой Текст

# [fit] Текст

---

# Название третьего слайда

1. Нумерованный список :sunny:    
1. Нумерованный список :umbrella:
1. Нумерованный список :sunflower:

- Ненумерованный список :cat:
- Ненумерованный список :smile:
- Ненумерованный список

- Вложенные списки
    1. отделяются
    1. отступами
    1. 4 пробела
- вот так вот

---

# Жирный, Курсив, Ссылка и т.д

**жирный**, __курсив__  либо **_оба_**.

[ссылка](http://valor-software.slack.com)

- ~~Strikethrough~~
- Сте<sup>пень</sup>
- Или<sub>так</sub>

---

# Код

```javascript	
 alert( 'Привет, Мир!' );
```

---

# Картинки

`‘![](ваша_картинка.jpg)’`

Картинка по дефолту заполняет весь экран, но если использовать и текст и картинку, картинкаразмыливаеися
и текст остается читаем
(гифки тоже работают)

---

# Картинки 2

![](valor_software.png)

Картинка по дефолту заполняет весь экран, но если использовать и текст и картинку, картинкаразмыливаеися
и текст остается читаем

---

#Картинки 3

# Для того, чтобы картинка была справа а слева текст, используйте следующее

```
### Этот текст будет слева от картинки, а сама картинка справа

![right](plant.jpg)
```

---

# Картинки слева или справа

#### Картинка по дефолту заполняет весь экран, но если использовать и текст и картинку, картинка размыливается и текст остается читаем

![right](valor_software.png)

---

# Видео

```
![autoplay](ролик.mov)
```

---

# Цитаты

Для цитаты используйте`‘>’` перед каждой цитируемой строкой
Используйте `‘--’` для уточнения чья это цитата

---

> Привет, Мир
-- Вася Пупкин

---

# Сноски

Обычные маркдауновые[^1] сноски[^Sample Footnote].

`[^Ваша Сноска]: Текст сноски`

[^1]: Сноска один

[^Sample Footnote]: Сноска два

---

# Таблицы

  Header 1 |    Header 2   |   Header 3   |
-----------| :-----------: | -----------: |
Cell       |     _Cell_    |     *Cell*
Cell       |   **Cell**    |     __Cell__

---

# Автоскейл текста

ОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТАОЧЕНЬ МНОГО ТЕКСТА