FROM python:3.8

# set working directory
WORKDIR /code

# install requirements
COPY ./requirements.txt /code/requirements.txt
RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

COPY . /code

CMD ["python3", "basic-assistant.py"]
