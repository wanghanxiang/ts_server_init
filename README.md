# ts_server_init
一个使用ts并且基于koa的基础服务

ps：数据一个基础的服务直接执行npm run dev 就可以运行。如果有丢失包 先yarn一下



##### 备注

1、src/config/config.dev.ts

里面可以配置dev环境的一些数据库配置（redis、mysql等数据）

2、路由的注册都是在controller中进行的

post, get, put, del添加装饰器即可
