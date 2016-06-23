# blog

这里用来存放我的blog所包含的文档

我的blog地址：[http://gaochen.github.io](http://gaochen.github.io)

注：

1. 在安装hexo的时候需要执行以下代码
```
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/pinggod/hexo-theme-apollo.git themes/apollo
```

2. hexo在部署(hexo d)的之前需要执行以下代码
```
npm install hexo-deployer-git --save
```

3. git push之前本地repo里用git log命令查看commit记录上的个人邮箱是否正确，否则Github没有记录Contributions