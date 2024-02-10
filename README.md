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
<!-- Tạo người dùng -->
Tạo người dùng API
# eis
