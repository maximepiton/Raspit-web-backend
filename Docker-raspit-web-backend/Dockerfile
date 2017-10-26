FROM ubuntu:latest

RUN apt update -y
RUN apt upgrade -y

RUN apt install -y python3 python3-pip curl
RUN pip3 install flask

RUN curl -SL https://www.earthsystemgrid.org/download/fileDownload.html?logicalFileId=154af009-fa02-11e6-a976-00c0f03d5b7c | tar xC .

CMD ["bash"]