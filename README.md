### Реализация тестового задания с префиксным деревом
#### Для запуска в коммандной строке, аргументы:
1. Путь до файла словаря
2. Слово по которому нужно получить позицию (Опционально)
3. Локаль по которой будут учитываться правила разбивки на слова (Опционально, по дефолту Locale.ENGLISH)

### Запуск проивзодится из командной строки из корня приложения, примеры:
    java -jar ./dist/test-work-1.0-jar-with-dependencies.jar
    java -jar ./dist/test-work-1.0-jar-with-dependencies.jar ./src/main/resources/example.txt Выражает

### Для сборки исходников используется команда
    mvn clean compile assembly:single