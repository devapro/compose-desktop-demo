FROM amd64/ubuntu
WORKDIR /app
RUN apt-get update && apt-get upgrade -y
RUN apt install wget -y
RUN apt install dpkg -y
RUN wget https://corretto.aws/downloads/resources/17.0.10.7.1/java-17-amazon-corretto-jdk_17.0.10.7-1_amd64.deb
RUN apt install java-common -y
RUN apt install fakeroot -y
RUN dpkg -i java-17-amazon-corretto-jdk_17.0.10.7-1_amd64.deb
RUN apt install libdpkg-dev -y