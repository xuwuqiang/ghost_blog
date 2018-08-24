*编辑环境数据库配置*
```
vim core/server/config/env/config.production.json
```

*安装依赖*
```
$ npm install --production
$ NODE_ENV=production knex-migrator init
```

*启动方式一二随意一个都可以*
```
//启动方式一
$ npm start --production
//启动方式二
$ NODE_ENV=production pm2 start index.js --name "blog"
