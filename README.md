# Создание теста для подготовки к экзамену
Идея создания такого проекта пришла мне при обучении в университете и подготовке к экзамену. Так как экзамен проходил в формате теста на онлайн платформе, я подумал, что если спарсить достаточное банк вопросов с платформы, то получится хорошо подготовиться к экзамену, и, в дальнейшем, продавать доступ к тесту-тренажеру студентам. 

Данный скрипт предназначен для сборки вопросов и ответов на них с платформы openedu(за данное действие отвечает файл pars.py с последующим вызовом main.py). 
Тесты на данном сайте выглядят следующим образом:![image](https://github.com/DayviLol/Test_for_students/assets/144832732/1a5b8986-9009-400d-8684-29b6ac7afc3e)
Количество тем - 14.

Так как вопросы у всех одинаковые, я брал аккаунты разных ребят и собирал те вопрос и ответы, которые есть у них, тем самым формируя общий банк вопросов.

После формирования БД в папке "Вопросы", формируется тест на сайте [onlinetestpad](https://onlinetestpad.com/). Парсер доходит до нужной директории, после чего создает тесты по собранным темам.
В зависимости от количества правильных вопросов скрипт выбирает вид ответа(множественный или одиночный выбор). 
![image](https://github.com/DayviLol/Test_for_students/assets/144832732/a73a2458-9313-4699-9c95-69ca002f7731)

Файл invites.py отвечает за предоставление доступа студентам к созданным тестам(такая система предусмотрена на данном сайте)
![image](https://github.com/DayviLol/Test_for_students/assets/144832732/fa91b73d-aac4-4877-96ac-f5489b4e3398)
