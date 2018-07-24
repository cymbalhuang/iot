git clone -b master https://github.com/emqtt/emq_docker.git

cd emq_docker

docker build -t emq:latest .

docker run -d -ti --name emq -p 18083:18083 -p 1883:1883 -p 8083:8083 emq

启动成功即可登录管理后台http://localhost:18083 进行发布订阅操作，默认用户密码admin/public
