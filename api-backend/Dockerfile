FROM python:3.6
WORKDIR /app
COPY . .
EXPOSE 3000
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "app.py"]
