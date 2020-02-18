
# Системные требования
- Java - 1.8.x
- Maven - 3.x.x
# Проект  реализован в .jar архиве
Варианты запуска:
1) Вариант ручной
 - download from git
 - mvn install || mvn spring-boot:run
2) Вариант через докер
 - cd /chat  - перейти в папку проекта
 - docker build -t chat . - собрать image
 - docker run -d chat - запустить проект в контейнере
 - проект будет доступен по http://192.168.99.100:8080