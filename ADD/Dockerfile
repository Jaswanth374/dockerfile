FROM almalinux:9
ADD https://roboshop-artifacts.s3.amazonaws.com/catalogue-v3.zip /tmp
# ADD /tmp/catalogue.zip /tmp
RUN dnf install unzip -y
RUN unzip /tmp/catalogue.zip /tmp