<!-- Tạo người dùng -->
"code-runner.runInTerminal": true
docker-compose up --build 
docker-compose down
<!--  -->
docker pull nats
docker save -o       nats_image.tar nats
docker load -i       nats_image.tar
<!--  -->
docker pull mysql
docker save -o       mysql_image.tar mysql
docker load -i       mysql_image.tar
<!--  --> 
docker pull node:18
docker save -o       node_image.tar node
docker load -i       node_image.tar
<!--  -->
Tạo người dùng API
npm -g nest
nest g resource   nghia
product  



=============================
=============================
=============================
npm i @nestjs/config
npm i @nestjs/swagger
npm i   faker
npm i        class-validator          class-transformer
npm i @nestjs/typeorm         typeorm  
npm i mysql2
npm i @nestjs/mongoose         mongoose  
npm i @nestjs/cqrs
npm i @nestjs/event-emitter 



npm i      @nestjs/microservices  
npm i        amqp-connection-manager   

