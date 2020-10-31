FROM python:3.7

MAINTAINEr Shashwat <shashwat.mishra@st.niituniversity.in>

ADD . E:\DockerCommon\Django-ToDo-App-with-PostgreSQL\TodoProject

WORKDIR E:\DockerCommon\Django-ToDo-App-with-PostgreSQL\TodoProject

COPY requirements.txt ./



RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]


