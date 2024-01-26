


### 解压包
unzip vue-element-admin-master.zip

mv ./vue-element-admin-master/{.,}* ./



具体如下：

1、打开package.json把"tui-editor"删掉

2、删除"tui-editor"相关路由、components，具体文件地址如下：

路由位置：
        src/router/modules/components.js 搜索"markdown"，把相应markdown路由代码删除；

components位置：
        src/components/MarkdownEditor 删除后，再执行npm install 或 npm install --registry=https://registry.npmmirror.com 下载并运行成功！

1. 代码提交前需配置eslint 检查。
   参考文档：https://zhuanlan.zhihu.com/p/48048906
   快捷键: option + command + L
触发构建

## 环境配置

node 版本 v10.16.3
npm install
npm run dev


Github地址： https://github.com/PanJiaChen/vue-element-admin



