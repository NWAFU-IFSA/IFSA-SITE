# HSD博客说明文档

## 构建环境与所用框架

项目使用`Node`版本为`v22.12.0`。无特殊需求请默认使用高于该版本的`Node`，并参考框架所需要求。注意，该服务器中hexo的npm模块使用`-g`参数安装。

```sh
$ npm install -g hexo-cli
```

博客基于[hexo](https://hexo.io/)与其[icarus](https://github.com/ppoffice/hexo-theme-icarus)主题构建。修改相关配置文件之前建议完整阅读前文所提项目文档。

## 目录结构

项目目录结构类似于典型的hexo项目，但是资源的组织形式上有改动。

```
.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   ├── _posts
|   └── images
|       └── covers
└── themes
```

`source/images`里存放了自定义资源文件；`source/images/covers`里存放文章的封面图片。

## 构建方式

参考 <https://hexo.io/docs/commands> 中的步骤进行。

## CI/CD化

参考[博客文章](https://blog.zyzh20021020.cn/2025/01/30/Hexo%E5%8D%9A%E5%AE%A2%E7%9A%84%E6%90%AD%E5%BB%BA%E4%B8%8E%E8%BF%81%E7%A7%BB%E8%87%B3%E8%85%BE%E8%AE%AF%E4%BA%91COS/)
