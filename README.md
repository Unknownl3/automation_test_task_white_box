### Предыстория 1

Вы — QA инженер на космическом корабле, который летит покорять новые галактики. Корабль новый и навороченный, но некоторые его части сделаны по принципу "работает — не трогай". Именно так реализован датчик температуры. Шел 2070 год, а к датчику все еще обращаются по HTTP 1.1 через GET-запросы. API принимает на вход параметр "?temperature=", в качестве выходных данных отдает вердикт — в каком состоянии будет вода при такой температуре.
Командир корабля попросил убедиться, что датчик "нормально работает". К сожалению, требований к датчику не сохранилось.

### Задание 1
Пожалуйста, напишите тесты на [API сервиса](http://ntanygin.pythonanywhere.com/) по анализу температуры. Мы хотим увидеть набор тестов, который поможет проверить, что датчик работает корректно, а космический корабль — не взорвется в холодном космическом пространстве. 

### Предыстория 2
Вы с коллегами проектируете главный графический интерфейс развлекательного экрана корабля, который показывает информацию на дисплеях. В процессе возникла сложность — разные части корабля заточены под разные технологии. Унифицировать их слишком тяжело и дорого, поэтому решено было просто поддержать разные версии всего.
Развлекательный экран должен работать с:
* английским и клингонским языками;
* соединяться и корректно работать с Postgres и MongoDB базами (да, прошло 50 лет, а ничего лучше так и не придумали);
* дисплеями моделей Nova и SuperNova.

### Задание 2
Составьте таблицу проверок, которая поможет удостовериться, что все будет работать как надо. Помните, что чем меньше проверок — тем лучше. 

### Задание 3
Пожалуйста, напишите 3 автотеста на интерфейс semrush.com.
* Тест 1: залониться под пользователем в SEMrush
* Тест 2: создайте новую заметку на /notes
* Тест 3: создайте новый проект

*Hint*: тесты должны стабильно проходить.

В качестве языка для реализации возьмите Java или Python. Вы можете выбрать любой подход, паттерн проектирования и фреймворк.

## Как и куда отправлять решение
 * Склонируйте себе репозиторий;
 * Оформите ваше решение в коде;
 * Отправьте pull request в этот репозиторий с вашим решением.
