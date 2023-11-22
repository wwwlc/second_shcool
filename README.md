### 前端代码

web文件

安装：npm install

运行：npm run dev

注意：login.vue文件需要改动，不然会有问题，编辑器CTRL+F搜“2728577785”改成个人qq，

### 后端代码

school文件

安装：npm install

运行：npm run serve

配置：

.env文件

```
APP_PORT = "5000" // 端口号，建议别改
MYSQL_HOST = "localhost"
MYSQL_PORT = "3306"
MYSQL_USER = "root"
MYSQL_DATABASE = "school" // 数据库名
MYSQL_PASSWORD = "root" // 数据库密码
MYSQL_PREFIX = "school_" // 表前缀，建议别改
CONNECTIONLIMIT = 10
```

### 数据库

school.sql