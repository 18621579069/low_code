## 开发

```bash
# 克隆项目
git clone https://gitee.com/open-source-byte/source-vue.git

# 进入项目目录
cd source-vue

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev 
```

浏览器访问 http://localhost:80

## 发布

```bash
# 构建
npm run build
```
