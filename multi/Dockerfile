FROM amazonlinux
RUN yum update
RUN yum install git -y
RUN yum install java-17 -y
RUN yum install maven -y
RUN git clone https://github.com/ramyachetty/vprofile-project.git
COPY . .
RUN cd vprofile-project && mvn clean install

