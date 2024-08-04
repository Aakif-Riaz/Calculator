# To create docker image, copy and paste the following code to Dockerfile and create image by executing this command in the vscode terminal; docker build -t calculator .

FROM python:3.11.6

WORKDIR /app

COPY calculator.py /app/

CMD ["python", "calculator.py"]
