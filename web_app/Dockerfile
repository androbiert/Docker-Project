FROM python:3.9-slim


WORKDIR /app


COPY . /app


RUN pip install  -r requirements.txt


EXPOSE 5000


# ENV FLASK_RUN_HOST=0.0.0.0


CMD ["python", "app.py"]


#pour excuter cette contonaire 
# aller au le web_app chemin
# docker build -t flask-app web_app/ sinon .
# docker run -d -p 8090:5000 flask-app