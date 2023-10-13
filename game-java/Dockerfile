FROM openjdk:17 
#используется как основа для сборки контейнера
LABEL version="1.0"
# версия 

WORKDIR /pr3/game-java
# рабочая дериктория 

COPY game.java /pr3/game-java/
# копирование рабочих файлов

CMD [ "java", "game.java" ]
# запуск необходимого файла