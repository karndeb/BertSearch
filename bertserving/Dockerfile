FROM tensorflow/tensorflow:1.12.0-py3
RUN pip install -U pip
RUN pip install --no-cache-dir bert-serving-server==1.10.0
COPY ./ /app
COPY ./entrypoint.sh /app
WORKDIR /app
ENTRYPOINT ["/app/entrypoint.sh"]
CMD []
