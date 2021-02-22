FROM ubuntu

RUN apt-get update && apt-get install -y git python3;
RUN git clone https://github.com/mubaris/motivate.git && cd motivate/motivate && ./install.sh;

CMD [ "motivate" ]