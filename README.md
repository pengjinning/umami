# umami

- nextjs入门： <https://nextjs.org/docs/getting-started>

```bash
# 安装node
# Using Ubuntu, 安装nodejs 16.x
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
# 安装yarn
npm install -g yarn
# 其他
node --version
npm --version
yarn --version
```

## 后台运行

```bash
# https://pm2.keymetrics.io/docs/usage/quick-start/
- yarn
- yarn build
- yarn start
# 后台运行：
- npm install pm2 -g
# 或者
- yarn global add pm2
# 启动
- pm2 start npm -- start
# 查看log
- pm2 logs
- pm2 logs --lines 200
# 监控
- pm2 monit

```

## 默认

- 用户名：admin
- 密码：umami
