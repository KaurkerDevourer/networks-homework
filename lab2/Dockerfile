FROM ubuntu

WORKDIR /workdir
COPY . .

RUN apt-get update && apt-get install -y iputils-ping
RUN apt-get update && apt-get install -y python3
RUN chmod +x script.py

CMD ["./script.py", "youtube.com"]
