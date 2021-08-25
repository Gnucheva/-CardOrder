[![Build status](https://ci.appveyor.com/api/projects/status/394sdu7i880oxtoy?svg=true)](https://ci.appveyor.com/project/Gnucheva/cardorder)

Вам необходимо автоматизировать тестирование формы заказа карты:
Требования к содержимому полей:
1. Поле Фамилия и имя - разрешены только русские буквы, дефисы и пробелы.
2. Поле телефон - только цифры (11 цифр), символ + (на первом месте).
3. Флажок согласия должен быть выставлен.

Тестируемая функциональность: отправка формы.   
Условия: если все поля заполнены корректно, то вы получаете сообщение об успешно отправленной заявке.   
Вам необходимо самостоятельно изучить элементы на странице, чтобы подобрать правильные селекторы.   
Проект с авто-тестами должен быть выполнен на базе Gradle, с использованием Selenide/Selenium (по выбору студента).   
Для запуска тестируемого приложения скачайте jar-файл из текущего каталога и запускайте его командой:
`java -jar app-order.jar`
Приложение будет запущено на порту 9999.

Если по каким-то причинам порт 9999 на вашей машине используется другим приложением, используйте:

`java -jar app-order.jar -port=7777`

Убедиться, что приложение работает, вы можете открыв в браузере страницу: http://localhost:9999

