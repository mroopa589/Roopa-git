FROM python:3.8slim
COPY ./app.py
WORKDIR /app.py
RUN pip install -r requirement.txt
RUN python -m spacy download en_core_web_sm
EXPOSE 8010
CMD ["python"."demo-test"]

