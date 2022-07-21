## Как запустить автотесты:
1. Установить Docker
2. Выполнить git clone https://github.com/HelgaMas/FinalProject.git
3. Открыть проект в Вашем редакторе кода (например IntelliJ IDEA)
4. Открыть терминал и выполнить команду docker-compose up
5. В другой вкладке терминала запустить проект командой java -jar aqa-shop.jar
6. Запустить тесты
7. После прохождения всех тестов выполнить команду gradlew allureServe (в новой вкладке терминала) для просмотра отчета по результатам выполнения тестов
