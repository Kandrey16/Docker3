FROM python:alpine
# используется как основа для сборки контейнера
LABEL version="1.0"
# версия

WORKDIR /pr3/python
# рабочая дериктория

COPY calc.py /pr3/python/
# копирование рабочих файлов

CMD [ "python", "calc.py" ]
# запуск необходимого файла