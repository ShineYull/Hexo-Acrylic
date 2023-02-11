---
title: 安装
cover: https://img2.acozycotage.net/i/2023/02/11/hdf3k1-1.webp
tags:
  - Acrylic
  - 主题文档
top_img: https://img2.acozycotage.net/i/2023/02/11/hdf3k1-1.webp
categories: Acrylic
abbrlink: 55021
---
## Git 安裝
在博客根目录里安装稳定版【推荐】

```powershell
git clone -b main https://github.com/hexo-theme-Acrylic/hexo-theme-Acrylic.git themes/Acrylic
```

## npm 安裝

暂未适配

## 应用主题

修改hexo配置文件`_config.yml`，把主题改为`Acrylic`

```yml
theme: Acrylic
```

>如果你没有pug以及stylus的渲染器，请下载安装： 
```shell
npm install hexo-renderer-pug hexo-renderer-stylus --save
```

## 更好的配置
- macos/linux
在博客根目录运行
```bash
cp -rf ./themes/Acrylic/_config.yml ./_config.Acrylic.yml
```
- windows
复制```/themes/Acrylic/_config.yml```此文件到hexo根目录，并重命名为```_config.Acrylic.yml```

## 报错？你得这样做（必做）
{% link source.zip,source资源,https://github.com/hexo-theme-Acrylic/JS-Acrylic/blob/main/source.zip %}
> 下载后解压后替换掉根目录的source文件夹