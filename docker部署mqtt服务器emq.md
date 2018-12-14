docker run --rm -tid --name emqx -p 18083:18083 -p 1883:1883 -p 4369:4369 -p 8883:8883 -p 8083:8083 -p 8084:8084 -p 8080:8080 emqx/emqx

启动成功即可登录管理后台http://localhost:18083 进行发布订阅操作，默认用户密码admin/public
