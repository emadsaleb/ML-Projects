From python:3.13
Run apt update -y && apt install awscli -y
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD["python3" , "app.py"]