FROM python:3.9-slim  
WORKDIR /app  
COPY . /app  
RUN pip install -r requirements.txt  
EXPOSE 8080  
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8080"]





# docker build -t fastapi-service .                      
# docker run --name database -p 5432:5432 -e POSTGRES_DB=student -e POSTGRES_PASSWORD=password -e POSTGRES_USER=postgres --network backend2 -d postgres
# docker run -d --network backend2 -p 8081:8080 fastapi-service
