FROM armv7/armhf-java8
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
# RUN docker run -d --hostname raspbabe --name rabbitMQ rabbitmq:3
CMD ["java", "-jar", "social-multiplication.jar"]
