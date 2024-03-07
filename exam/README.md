# 项目介绍及启动说明

> 在线考试系统-前端项目文件。

### 系统架构

### 安装建议

> 建议使用`yarn`来安装项目依赖，首先安装yarn，然后设置yarn源为淘宝镜像

``` bash
# 安装yarn
npm install yarn -g

# 查看是否安装成功
yarn -v

# 设置yarn源为淘宝镜像源
yarn config set registry https://registry.npm.taobao.org

# 安装依赖
yarn install or npm install

# 启动项目
yarn dev or npm run dev

# 打包构建
yarn build or npm run build

#清缓存
npm cache clear --force

```
### 出错解决

``` bash
#注册表重置
npm config set registry http://registry.npmjs.org/

#There appears to be trouble with your network connection
① 检查配置文件
yarn config list
② 手动更新配置文件
yarn config set registry https://registry.npm.taobao.org
npm config set registry https://registry.npm.taobao.org
npm config set disturl https://npm.taobao.org/dist
npm config set 'https://registry.npmjs.org/'
③ 删除无用配置项
yarn config delete 配置项名
npm config delete 配置项名
```
