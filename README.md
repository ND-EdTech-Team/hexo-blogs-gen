# hexo-blogs-gen
技术博客生成工具脚本，用于blogs下博客的生成脚本工程

# 使用方法
请确保工作环境安装： Nodejs 且版本 >= 8.x

```shell
// 推荐用yarn
npm -g i hexo
npm i

// 创建博客名
hexo new ${TITLE}

// 本地开发调试预览
hexo s

// 本地站点生成
hexo g

// 推送 blogs 项目 github pages（需要权限或者登陆）
hexo deploy

// 清空缓存
hexo clean

// 删除请到 source/_posts 下删除，同时执行 hexo clean
```
