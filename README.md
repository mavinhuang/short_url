# ShortUrl

> 短链接生成应用

## 系统设计

[短网址(short URL)系统的原理及其实现](https://hufangyun.com/2017/short-url/)

## 准备工作

###  安装elixir

http://elixir-lang.org/install.html

### 安装postgreSQL

## 首次运行

  * 安装依赖  `mix deps.get`
  * 创建数据库及数据表  `mix ecto.create && mix ecto.migrate`
  * 安装前端依赖 `cd assets && yarn install`
  * 启动服务 `mix phx.server`
  * 访问应用 [`localhost:4000`](http://localhost:4000)

## 调试

进入控制台:

```shell
iex -S mix
```

## 格式化代码

```
mix format
```
## 部署

可以参考这篇文章 [使用 edeliver 部署 Elixir 应用程序](https://hufangyun.com/2017/elixir-edeliver/)

## 配置

1、部署地址

2、短链域名

## TODO

- [ ] 更新 README.md 关于接口的使用

- [ ] 记录打包、部署、更新测试中的地址
