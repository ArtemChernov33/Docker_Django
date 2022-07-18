FROM python:3.9

ENV PYTHONUNBUFFERED 1
COPY ./requirements.txt /src/requirements.txt
RUN pip install --no-cache-dir --upgrade -r /src/requirements.txt
WORKDIR /src
COPY . /src


EXPOSE 8000



CMD ["python3", "-u", "manage.py", "runserver", "0.0.0.0:8000"]



