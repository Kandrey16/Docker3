FROM python:alpine
# используется как основа для сборки контейнера
LABEL version="1.0"
# версия

WORKDIR /pr3/docker
# рабочая дериктория

COPY test.py /pr3/docker/
# копирование рабочих файлов

CMD [ "python", "test.py" ]
# запуск необходимого файла