FROM python:3.7
WORKDIR /usr/src/app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 3000 
ENTRYPOINT ["python"]
CMD ["./app.py"]